<template>
  <div class="bg-blue-900 w-screen h-screen">
    <div class="flex flex-col  ">
      <h1 class="text-2xl font-bold mt-10 text-white">
        Informacion General
      </h1>

      <form class="w-full max-w-lg self-center mt-8 ">
        <div class="flex flex-wrap -mx-3 mb-6">
          <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
            <label
              class="block uppercase tracking-wide text-white text-xs
           mb-2 "
              for="grid-first-name"
            >
              Nombre:
            </label>
            <input
              class="appearance-none block w-full bg-gray-200 text-white border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
              id="grid-first-name"
              type="text"
              placeholder="Cynthia Torres"
            />
            <!-- <p class="text-red-500 text-xs italic">Please fill out this field.</p> -->
          </div>
          <div class="w-full md:w-1/2 px-3">
            <label
              class="block uppercase tracking-wide text-white text-xs mb-2"
              for="grid-last-name"
            >
              Nombre del artista:
            </label>
            <input
              class="appearance-none block w-full bg-gray-200 text-white border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
              id="grid-last-name"
              type="text"
              placeholder="Recrow"
            />
          </div>
        </div>
        <div class="flex flex-wrap -mx-3 mb-2">
          <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
            <label class="block uppercase tracking-wide text-white text-xs  mb-2" for="grid-city">
              Edad:
            </label>
            <input
              class="appearance-none block w-full bg-gray-200 text-white border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
              id="grid-city"
              type="text"
              placeholder="20 años"
            />
          </div>
          <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
            <label class="block uppercase tracking-wide text-white text-xs  mb-2" for="grid-city">
              Numero de contacto:
            </label>
            <input
              class="appearance-none block w-full bg-gray-200 text-white border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
              id="grid-city"
              type="text"
              placeholder="8117210920"
            />
          </div>
          <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
            <label class="block uppercase tracking-wide text-white text-xs  mb-2" for="grid-city">
              Metodo de pago:
            </label>
            <select
              class="block appearance-none w-full bg-gray-200 border border-gray-200 text-gray-700 py-3 px-4 pr-8 rounded leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
              id="grid-state"
            >
              <option>Tarjetazo</option>
              <option>Efectivo</option>
              <option>Cheque</option>
            </select>
          </div>
        </div>
        <div class="flex flex-wrap -mx-3 mb-6 mt-5">
          <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
            <label
              class="block uppercase tracking-wide text-white text-xs
           mb-2 "
              for="grid-first-name"
            >
              Link del portafolio:
            </label>
            <input
              class="appearance-none block w-full bg-gray-200 text-white border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
              id="grid-first-name"
              type="text"
              placeholder="www.instagram.com/recrow.art"
            />
            <!-- <p class="text-red-500 text-xs italic">Please fill out this field.</p> -->
          </div>
          <div class="w-full md:w-1/2 px-3">
            <label
              class="block uppercase tracking-wide text-white text-xs mb-2"
              for="grid-last-name"
            >
             Correo electronico:
            </label>
            <input
              class="appearance-none block w-full bg-gray-200 text-white border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
              id="grid-last-name"
              type="text"
              placeholder="recrowart@artistalley.com"
            />
          </div>
        </div>
        <div class="mt-8">
          <button
            class="shadow bg-purple-500 hover:bg-purple-400 focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded"
            type="button"
          >
            Enviar
          </button>
        </div>
      </form>
    </div>
  </div>
</template>
