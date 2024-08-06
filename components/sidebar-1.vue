<template>
  <div class="relative lg:left-80 md:left-80 lg:ml-auto md:ml-auto container mx-auto p-5">
    Content
  </div>
  <div class="h-screen flex items-end justify-end px-4 pb-6">
    <button class="relative z-30 lg:hidden md:hidden peer h-14 w-14 rounded-full bg-cyan-500 hover:bg-cyan-600 focus:bg-cyan-600 active:bg-cyan-700 transition">
      <span class="text-white">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-6 m-auto" viewBox="0 0 16 16">
          <path fill-rule="evenodd" d="M3.646 9.146a.5.5 0 0 1 .708 0L8 12.793l3.646-3.647a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 0 1 0-.708zm0-2.292a.5.5 0 0 0 .708 0L8 3.207l3.646 3.647a.5.5 0 0 0 .708-.708l-4-4a.5.5 0 0 0-.708 0l-4 4a.5.5 0 0 0 0 .708z"/>
        </svg>
      </span>
    </button>

    <div class="z-20 fixed top-0 -left-96 lg:left-0 md:left-0 h-screen w-9/12 lg:w-72 md:w-60 bg-white shadow-2xl peer-focus:left-0 peer:transition ease-out delay-150 duration-200">
      <nav role="navigation" class="p-6">
          <div class="flex items-center gap-4 pb-4">
            <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600" alt="" />
            Tailwind Sidebar
          </div>

          <div class="relative">
            <form action="" class="text-gray-500 focus-within:text-cyan-400 focus-within:bg-white focus-within:shadow rounded search transition duration-300">
              <div class="relative w-full">
                <div class="absolute top-0 bottom-0 h-full flex items-center mb-auto left-4">
                  <svg xmlns="http://ww50w3.org/2000/svg" class="w-4 fill-current" viewBox="0 0 35.997 36.004">
                    <path id="Icon_awesome-search" data-name="search" d="M35.508,31.127l-7.01-7.01a1.686,1.686,0,0,0-1.2-.492H26.156a14.618,14.618,0,1,0-2.531,2.531V27.3a1.686,1.686,0,0,0,.492,1.2l7.01,7.01a1.681,1.681,0,0,0,2.384,0l1.99-1.99a1.7,1.7,0,0,0,.007-2.391Zm-20.883-7.5a9,9,0,1,1,9-9A8.995,8.995,0,0,1,14.625,23.625Z"></path>
                  </svg>
                </div>
                <input type="search" placeholder="Search  " name="search" id="search" class="text-sm text-gray-500 placeholder-gray-500 w-full rounded py-3 pr-4 pl-12 bg-gray-200 bg-opacity-75 outline-none focus:bg-transparent focus:rounded-3xl transition-all" />
              </div>
            </form>
          </div>

          <div class="mt-4 -mx-4 relative overflow-y-auto overflow-x-hidden h-[85vh]">
            <span class="uppercase px-4 text-gray-500">Menu</span>
            <ul class="space-y-4 mb-12 px-4 mt-8">
              <li>
                <a href="" class="flex gap-4 text-gray-600 hover:text-gray-800 transition">
                  <svg xmlns="http://www.w3.org/2000/svg" width="32" height="24" viewBox="0 0 256 168"><path fill="#00DC82" d="M143.618 167.029h95.166c3.023 0 5.992-.771 8.61-2.237a16.96 16.96 0 0 0 6.302-6.115a16.3 16.3 0 0 0 2.304-8.352c0-2.932-.799-5.811-2.312-8.35L189.778 34.6a16.97 16.97 0 0 0-6.301-6.113a17.6 17.6 0 0 0-8.608-2.238c-3.023 0-5.991.772-8.609 2.238a16.96 16.96 0 0 0-6.3 6.113l-16.342 27.473l-31.95-53.724a17 17 0 0 0-6.304-6.112A17.64 17.64 0 0 0 96.754 0c-3.022 0-5.992.772-8.61 2.237a17 17 0 0 0-6.303 6.112L2.31 141.975a16.3 16.3 0 0 0-2.31 8.35c0 2.932.793 5.813 2.304 8.352a16.96 16.96 0 0 0 6.302 6.115a17.6 17.6 0 0 0 8.61 2.237h59.737c23.669 0 41.123-10.084 53.134-29.758l29.159-48.983l15.618-26.215l46.874 78.742h-62.492zm-67.64-26.24l-41.688-.01L96.782 35.796l31.181 52.492l-20.877 35.084c-7.976 12.765-17.037 17.416-31.107 17.416"/></svg>
                  Menu 1
                </a>
              </li>
              <li>
                <a href="" class="flex gap-4 text-gray-600 hover:text-gray-800 transition">
                  <svg xmlns="http://www.w3.org/2000/svg" width="32" height="24" viewBox="0 0 256 168"><path fill="#00DC82" d="M143.618 167.029h95.166c3.023 0 5.992-.771 8.61-2.237a16.96 16.96 0 0 0 6.302-6.115a16.3 16.3 0 0 0 2.304-8.352c0-2.932-.799-5.811-2.312-8.35L189.778 34.6a16.97 16.97 0 0 0-6.301-6.113a17.6 17.6 0 0 0-8.608-2.238c-3.023 0-5.991.772-8.609 2.238a16.96 16.96 0 0 0-6.3 6.113l-16.342 27.473l-31.95-53.724a17 17 0 0 0-6.304-6.112A17.64 17.64 0 0 0 96.754 0c-3.022 0-5.992.772-8.61 2.237a17 17 0 0 0-6.303 6.112L2.31 141.975a16.3 16.3 0 0 0-2.31 8.35c0 2.932.793 5.813 2.304 8.352a16.96 16.96 0 0 0 6.302 6.115a17.6 17.6 0 0 0 8.61 2.237h59.737c23.669 0 41.123-10.084 53.134-29.758l29.159-48.983l15.618-26.215l46.874 78.742h-62.492zm-67.64-26.24l-41.688-.01L96.782 35.796l31.181 52.492l-20.877 35.084c-7.976 12.765-17.037 17.416-31.107 17.416"/></svg>
                  Menu 2
                </a>
              </li>
              <li>
                <a href="" class="flex gap-4 text-gray-600 hover:text-gray-800 transition">
                  <svg xmlns="http://www.w3.org/2000/svg" width="32" height="24" viewBox="0 0 256 168"><path fill="#00DC82" d="M143.618 167.029h95.166c3.023 0 5.992-.771 8.61-2.237a16.96 16.96 0 0 0 6.302-6.115a16.3 16.3 0 0 0 2.304-8.352c0-2.932-.799-5.811-2.312-8.35L189.778 34.6a16.97 16.97 0 0 0-6.301-6.113a17.6 17.6 0 0 0-8.608-2.238c-3.023 0-5.991.772-8.609 2.238a16.96 16.96 0 0 0-6.3 6.113l-16.342 27.473l-31.95-53.724a17 17 0 0 0-6.304-6.112A17.64 17.64 0 0 0 96.754 0c-3.022 0-5.992.772-8.61 2.237a17 17 0 0 0-6.303 6.112L2.31 141.975a16.3 16.3 0 0 0-2.31 8.35c0 2.932.793 5.813 2.304 8.352a16.96 16.96 0 0 0 6.302 6.115a17.6 17.6 0 0 0 8.61 2.237h59.737c23.669 0 41.123-10.084 53.134-29.758l29.159-48.983l15.618-26.215l46.874 78.742h-62.492zm-67.64-26.24l-41.688-.01L96.782 35.796l31.181 52.492l-20.877 35.084c-7.976 12.765-17.037 17.416-31.107 17.416"/></svg>
                  Menu 3
                </a>
              </li>
              <li>
                <a href="" class="flex gap-4 text-gray-600 hover:text-gray-800 transition">
                  <svg xmlns="http://www.w3.org/2000/svg" width="32" height="24" viewBox="0 0 256 168"><path fill="#00DC82" d="M143.618 167.029h95.166c3.023 0 5.992-.771 8.61-2.237a16.96 16.96 0 0 0 6.302-6.115a16.3 16.3 0 0 0 2.304-8.352c0-2.932-.799-5.811-2.312-8.35L189.778 34.6a16.97 16.97 0 0 0-6.301-6.113a17.6 17.6 0 0 0-8.608-2.238c-3.023 0-5.991.772-8.609 2.238a16.96 16.96 0 0 0-6.3 6.113l-16.342 27.473l-31.95-53.724a17 17 0 0 0-6.304-6.112A17.64 17.64 0 0 0 96.754 0c-3.022 0-5.992.772-8.61 2.237a17 17 0 0 0-6.303 6.112L2.31 141.975a16.3 16.3 0 0 0-2.31 8.35c0 2.932.793 5.813 2.304 8.352a16.96 16.96 0 0 0 6.302 6.115a17.6 17.6 0 0 0 8.61 2.237h59.737c23.669 0 41.123-10.084 53.134-29.758l29.159-48.983l15.618-26.215l46.874 78.742h-62.492zm-67.64-26.24l-41.688-.01L96.782 35.796l31.181 52.492l-20.877 35.084c-7.976 12.765-17.037 17.416-31.107 17.416"/></svg>
                  Menu 4
                </a>
              </li>
            </ul>
            <ul class="space-y-4">
              <li class="pr-2">
                <div class="py-2 px-4 text-gray-700 uppercase">
                  <a href="" class="block">Other Menu</a>
                </div>
                <ul class="text-sm pb-24">
                  <li>
                    <a href="" class="block py-2 px-5 rounded bg-cyan-500 bg-opacity-10 hover:bg-opacity-20 text-cyan-500">Alert</a>
                  </li>
                  <li>
                    <a class="block py-2 px-5 hover:text-gray-800 transition" href="">Other 1</a>
                  </li>
                  <li>
                    <a class="block py-2 px-5 hover:text-gray-800 transition" href="">Other 2</a>
                  </li>
                  <li>
                    <a class="block py-2 px-5 hover:text-gray-800 transition" href="">Other 3</a>
                  </li>
                  <li>
                    <a class="block py-2 px-5 hover:text-gray-800 transition" href="">Other 4</a>
                  </li>
                </ul>
              </li>
            </ul>
          </div>
        </nav>
    </div>

    <div class="z-10 fixed top-0 left-0 w-screen h-screen bg-gray-900 bg-opacity-30 opacity-0 peer-focus:opacity-100 peer:transition duration-200"></div>
  </div>
</template>

<script setup>

</script>