# demo_using-tailblocks
1st Tailwind css site


<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <!-- <link rel='stylesheet' type='text/css' media='screen' href='main.css'> -->
    <!-- <script src='main.js'></script> -->
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">

</head>

<body>
    <!-- header start -->
    <header class="text-gray-500 bg-gray-900 body-font">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
          <a class="flex title-font font-medium items-center text-white mb-4 md:mb-0">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
              <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
            </svg>
            <span class="ml-3 text-xl">DLabzAerospcae</span>
          </a>
          <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
            <a class="mr-5 hover:text-white">An Aerospcae Startup</a>
          </nav>
        </div>
      </header>
    <!-- header end -->

    <!-- intro start -->
    <section >
    <div class="bi" style="background: url(/images/Wallpaper.png);">    
        <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center" style="background: url('/images/Wallpaper.png')">
        <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-black">Before they sold out
            <br class="hidden lg:inline-block">readymade gluten
        </h1>
        <p class="mb-8 leading-relaxed">Copper mug try-hard pitchfork pour-over freegan heirloom neutra air plant cold-pressed tacos poke beard tote bag. Heirloom echo park mlkshk tote bag selvage hot chicken authentic tumeric truffaut hexagon try-hard chambray.</p>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
        <img class="object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600">
        </div>
        </div>
    </div>

    </section>
    <!-- intro ends -->

    <!--  -->
</body>
</html>
