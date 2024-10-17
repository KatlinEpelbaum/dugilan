<template>
  <header class="flex justify-between items-center px-32 py-4">
    <div class="flex">
      <img src="./img/Logo.svg" alt="">
        <button class="px-6"> Browse</button>
        <button class="px-4">All-Exclusive</button>
        <button class="px-4">Docs</button>
    </div>
    <div class="flex">
      <div class="flex p-4">
        <input type="text" name="search">
        <button ><img src="./img/search.svg" alt=""></button>
      </div>
      <img class="px-4" src="./img/heart.svg" alt="">
      <img class="px-4 pr-6" src="./img/shopping-bag.svg" alt="">
      <button class="bg-sky-500 text-white  py-2 px-6 rounded">Account</button>
    </div>
  </header>
  <section class="flex justify-between items-center p-4">
  <div class="flex flex-col pl-28 flex-1">
    <p class="bg-sky-100 rounded-lg text-sky-400 w-32 text-center">Christmas sale</p>
    <h1 class="text-4xl font-bold pt-4 pb-6">Woocommerce <br> Figma UI Kit & <br> Template</h1>
    <div class="pb-6 flex">
      <input class="p-4 pr-20 border border-gray-300 rounded-l-md focus:outline-none focus:ring-2 focus:ring-sky-500 flex-1" type="text" placeholder="e.g Responsive header">
      <button class="h-full bg-sky-500 text-white py-4 px-8 rounded-r-md border border-gray-300">Search</button>
    </div>
    <p class="text-gray-600">From multipurpose themes to niche templates, <br>you’ll always find something that catches your eye.</p>
  </div>
  <div class="flex-col flex justify-center">
    <img class="max-w-full h-auto" src="./img/mockup2.png" alt="">
    <p class="text-sky-500 text-lg font-bold text-start pt-6">Some of our 500 clients already using Dugilan</p>
  </div>
</section>
<section class="px-28 pb-20 mt-6">
    <div class="flex justify-between items-center">
      <img src="./img/acer.png" alt="">
      <img src="./img/facebook.png" alt="">
      <img src="./img/linkedin.png" alt="">
      <img src="./img/forbes.png" alt="">
      <img src="./img/dell.png" alt="">
    </div>
  </section>
<section class="px-24 py-12">
    <div class="flex justify-center space-x-12">
      <div class="space-y-12">
        <div class="rounded-lg border-2">
          <div class="bg-sky-500 rounded-t-lg p-4 ">
            <h2 class="text-xl text-white font-semibold">Browse categories</h2>
          </div>
          <ul class="space-y-4 divide-y-2">
            <li class="flex gap-2 px-4 pt-4"><img src="./img/home.svg" alt="">Home</li>
            <li class="flex gap-2 px-4 pt-4"><img src="./img/wordpress.svg" alt="">Wordpress Themes</li>
            <li class="flex gap-2 px-4 pt-4"><img src="./img/shopping-cart.svg" alt="">eCommerce Templates</li>
            <li class="flex gap-2 px-4 pt-4"><img src="./img/tv.svg" alt="">Marketing Templates</li>
            <li class="flex gap-2 px-4 pt-4"><img src="./img/grid.svg" alt="">CMS Templates</li>
            <li class="flex gap-2 px-4 pt-4"><img src="./img/monitor.svg" alt="">Site Templates</li>
            <li class="flex gap-2 px-4 py-4"><img src="./img/edit.svg" alt="">Blogging</li>

          </ul>
        </div>
        <div class="flex flex-col items-center p-8 bg-sky-50 space-y-6 rounded-xl text-center">
          <h2 class="font-semibold text-lg">Subscribe Newsletter</h2>
          <p>Get all the latest information on<br> Events, Sales and Offers.</p>
          <div class="flex space-x-2 bg-white p-4 rounded-lg">
            <img src="./img/mail.svg" alt="">
            <input type="email" name="" placeholder="Email Adress" id="">
          </div>
          <button class="bg-sky-100 text-sky-600 w-full py-4 rounded-lg">Subscribe</button>
        </div>
        <div class="flex items-center flex-col space-y-6 text-center border p-8 rounded-xl">
          <img src="./img/circle.svg" alt="">
          <h2 class="text-xl font-semibold">Monthly users in your site</h2>
          <h1 class="text-sky-500 font-bold text-3xl">1.0286</h1>
          <p class="text-gray-400 font-sm">We accompany you with our<br> versatile expertise in digital marketing</p>
        </div>
        <div class="bg-yellow-50 flex flex-col items-center text-center space-y-6 pb-6 rounded-lg">
          <img src="./img/squarespace.png" alt="">
          <p>Create your beautiful portfolio<br> website with Squarespace. Start<br> your free trial.</p>
          <p>Ads via Carbon</p>
        </div>
      </div>
      <div class="w-3/4 space-y-8">
        <div class="block">
          <div class="flex justify-between items-center">
            <h1 class="underline underline-offset-8 text-2xl decoration-sky-600 font-semibold">New Products</h1>
            <p class="text-sky-600">See All New Products</p>
          </div>
        </div>
        <div class="grid grid-cols-3 grid-rows-3 gap-6 mt-12 pb-6">
          <div class="space-y-4">
            <img src="./img/abstractbanner.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract2.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract3.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract4.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract5.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract6.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract7.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract8.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract9.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          
        </div>
        <div class="bg-sky-100 flex justify-center p-4 space-x-2 rounded-lg">
          <img src="./img/figma.svg" alt="">
          <p class="border-l-2 pl-2 border-sky-600">More than 200 untouched Vector Flags for Figma</p>
          <h2 class="font-semibold text-sky-600">Get them now</h2>
        </div>
        <div class="space-x-6 pt-6">
          <a href="" class="text-xl font-semibold underline underline-offset-8 decoration-sky-600">Headers</a>
          <a href="" class="text-xl font-semibold">Hero Section</a>
          <a href="" class="text-xl font-semibold">Blog Page</a>
          <a href="" class="text-xl font-semibold">CTA Sections</a>
          <a href="" class="text-xl font-semibold">Footers</a>
        </div>
        <div class="grid grid-cols-3 grid-rows-3 gap-6 mt-12">
          <div class="space-y-4">
            <img src="./img/abstractbanner.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract2.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract3.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract4.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract5.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract6.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract7.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract8.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          <div class="space-y-4">
            <img src="./img/abstract9.png" class="w-full rounded-lg" alt="">
            <div class="flex items-start justify-between">
              <div>
                <h2 class="font-semibold">Abstract Theme</h2>
                <p class="text-gray-400">PHP, Wordpress</p>
              </div>
              <div class="bg-sky-100  text-sky-600 text-center flex items-center justify-center p-2 rounded-lg">
                $29,99
              </div>
            </div>
          </div>
          
        </div>
      </div>
      
      
    </div>
  </section> 
  
<section class="bg-sky-100 flex justify-between ">
  <div class="flex flex-col pl-32 pt-36">
    <h1 class="text-4xl font-bold pt-4 pb-6 text-sky-500">We build apps and <br> websites</h1>
    <p class="text-gray-700 pb-4 w-max">From multipurpose themes to niche templates, <br> you’ll always find something that catches your eye.</p>
    <div class="flex space-x-4">
      <button class="bg-sky-500 text-white py-4 px-6 rounded">Contact Us</button>
      <button class="px-6 font-bold text-gray-600">or see our portfolio</button>
    </div>
  </div>
  <div class="flex">
    <img class="max-w-full h-full bottom-0" src="./img/Mask Group.png" alt="">
  </div>
</section>

  <footer>
    <div class=" py-20 flex justify-between items-center px-20">
      <div >
        <h3 class="font-bold pb-4">Envato Market</h3>
        <p class="pb-4">Terms</p>
        <p class="pb-4">Licenses</p>
        <p class="pb-4">Market API</p>
        <p>Become an affiliate</p>
      </div>

      <div>
        <h3 class="font-bold pb-4">Help</h3>
        <p class="pb-4">Themes and Templates</p>
        <p class="pb-4">Authors</p>
        <p class="pb-4">Help Center</p>
        <p>Become an affiliate</p>
      </div>

      <div>
        <h3 class="font-bold pb-4">Our Community</h3>
        <p class="pb-4">Community</p>
        <p class="pb-4">Blog</p>
        <p class="pb-4">Forums</p>
        <p class="pb-4">Meetups</p>
      </div>

      <div>
        <h3 class="font-bold pb-4">Contact</h3>
        <p class="pb-4">Sabri Hakuli</p>
        <p class="pb-4">sabrihakuli@outlook.com</p>
        <p>+383 44 201 874</p>
      </div>
    </div>
    <div class="border-2 flex justify-between items-center px-32 py-4">
      <p class="mr-4 text-gray-600">© 2022 DugiLanding All rights reserved.</p>
      <div class="flex space-x-2">
        <img class="h-auto" src="./img/Frame.png" alt="">
        <img class="h-auto" src="./img/Frame (1).png" alt="">
        <img class="h-auto" src="./img/Frame (2).png" alt="">
        <img class="h-auto" src="./img/Frame (3).png" alt="">
        <img class="h-auto" src="./img/Frame (4).png" alt="">
      </div>
    </div>
  </footer>

</template>
