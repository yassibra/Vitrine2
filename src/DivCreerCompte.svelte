<div class="mx-auto flex min-h-screen w-full items-center justify-center bg-gray-900 text-white">
  <section class="flex w-[30rem] flex-col space-y-10">
      <div class="text-center text-4xl font-medium">Creez un compte</div>
       <div
        class="w-full transform border-b-2 bg-transparent text-lg duration-300 focus-within:border-indigo-500"
      >
        <input
          type="text"
          placeholder="Pseudo"
          class="w-full border-none bg-transparent outline-none placeholder:italic focus:outline-none"
        />
      </div>

      <div
        class="w-full transform border-b-2 bg-transparent text-lg duration-300 focus-within:border-indigo-500"
      >
        <input
          type="text"
          placeholder="Email"
          class="w-full border-none bg-transparent outline-none placeholder:italic focus:outline-none"
        />
      </div>

      <div
        class="w-full transform border-b-2 bg-transparent text-lg duration-300 focus-within:border-indigo-500"
      >
        <input
          type="password"
          placeholder="Mot de passe"
          class="w-full border-none bg-transparent outline-none placeholder:italic focus:outline-none"
        />
      </div>
      <div
        class="w-full transform border-b-2 bg-transparent text-lg duration-300 focus-within:border-indigo-500 inline-block"
      >
        <input
          type="password"
          placeholder="Confirmez mot de passe" 
          class="w-full border-none bg-transparent outline-none placeholder:italic focus:outline-none inline-block"
        />
        <svg id="boutonrouge" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-4 h-4 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>

      </div>

      <button
        class="transform rounded-sm bg-indigo-600 py-2 font-bold duration-300 hover:bg-indigo-400"
      >
       Creer un compte 
      </button>

      <a
        href="#"
        class="transform text-center font-semibold text-gray-500 duration-300 hover:text-gray-300"
        >Mot de passe oublié ?</a
      >

      <p class="text-center text-lg">
        Déjà un compte ?
        <a
          href="#/connexion"
          class="font-medium text-indigo-500 underline-offset-4 hover:underline"
          >Se connecter </a
        >
      </p>
    </section>
  </div>

  <style>
  #boutonrouge{
  display: inline-block;
  float: right;
  }
  </style>