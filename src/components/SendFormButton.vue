<template>
  <div>
    <div class="mt-8">
      <button
        @click="submitForm"
        :disabled="sendForm"
        :class="buttonClasses"
        type="button"
      >
        Enviar
      </button>
    </div>
    <div v-if="sendForm" class="bg-green-100 border-t border-b border-green-500 text-green-700 px-4 py-3 mt-4" role="alert">
      <p class="font-bold">¡{{ name }} tu registro fue éxitoso!</p>
      <p class="text-sm">Pronto recibirias un correo de confirmación</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SendFormButton',
  props: ['name'],
  data() {
    return {
      sendForm: false,
    };
  },
  methods: {
    submitForm() {
      this.sendForm = true;
    },
  },
  computed: {
    buttonClasses() {
      return this.sendForm
        ? 'bg-blue-500 text-white font-bold py-2 px-4 rounded opacity-50 cursor-not-allowed'
        : 'shadow bg-purple-500 hover:bg-purple-400 focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded';
    },
  },
};
</script>
