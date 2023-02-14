<template>
    <section class="py-20">
        <div class="container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-[30px]">
                <div class="lg:col-span-3">
                    <div class="sticky top-[90px]">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">Documentation</h5>
                            </div>
                            <nav class="p-[26px]">
                                <ul class="space-y-2.5 doc-nav">
                                    <li class="intro active"><a href="#intro">Introduction</a></li>
                                    <li class="installation"><a href="#installation">Installation</a></li>
                                    <li class="file_structure"><a href="#file_structure">File Structure</a></li>
                                    <li class="html"><a href="#html">HTML</a></li>
                                    <li class="css"><a href="#css">CSS</a></li>
                                    <li class="javascript"><a href="#javascript">Javascript</a></li>
                                    <li class="features"><a href="#features">Features</a></li>
                                    <li class="credit"><a href="#credit">Credit &amp; Resources</a></li>
                                    <li class="support"><a href="#support">Support</a></li>
                                </ul>
                            </nav>
                        </div>
                    </div>
                </div>
                <section class="lg:col-span-9 space-y-5">
                    <section id="intro">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">Introduction</h5>
                            </div>
                            <div class="p-[26px]">
                                <p class="text-lg text-muted">Landik is a superb, one of a kind, and present day HTML5
                                    Template having multi-choices for Startups, App Landing, and SaaS-based companies.
                                    It has 4 special points of arrival with multi internal pages for different purposes.
                                </p>
                            </div>
                        </div>
                    </section>
                    <section id="installation">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">Installation</h5>
                            </div>
                            <div class="p-[26px]">
                                <p class="text-lg font-semibold">To setup the admin theme, follow below-mentioned steps
                                </p>
                                <ul class="mt-3 list-decimal list-inside space-y-2">
                                    <li>The zip file contains all files integrated with Landik, however you need to
                                        perform following steps to get node_modules etc.</li>
                                    <li>Note : Make sure this all installation process is done in command prompt.</li>
                                    <li>make sure you have installed tailwindcss in your os. If not installed then
                                        please run the below command to install it globally. <code
                                            class="text-[#e83e8c]">npm install</code></li>
                                    <li>After Completion of installation Run the following command in the command prompt
                                        to start tailwindcss development server. <code
                                            class="text-[#e83e8c]">npm run dev </code></li>

                                </ul>
                            </div>
                        </div>
                    </section>
                    <section id="file_structure">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">File Structure</h5>
                            </div>
                            <div class="p-[26px] overflow-x-auto w-full">
                                <pre class="prettyprint">
<i class="mdi mdi-folder-multiple"></i> Landik/
├── <i class="mdi mdi-folder-multiple"></i> landing/
│   ├── <i class="mdi mdi-folder-multiple"></i> assets/
│   │   ├── <i class="mdi mdi-folder-multiple"></i> css/
│   │   │   └── <i class="mdi mdi-file-multiple"></i> All css files
│   │   ├── <i class="mdi mdi-folder-multiple"></i> fonts/
│   │   │   └── <i class="mdi mdi-file-multiple"></i> All font files
│   │   ├── <i class="mdi mdi-folder-multiple"></i> images/
│   │   │   └── <i class="mdi mdi-file-multiple"></i> All images files
│   │   └── <i class="mdi mdi-folder-multiple"></i> js
│   │       └── <i class="mdi mdi-file-multiple"></i> All javascript files
│   ├── <i class="mdi mdi-folder-multiple"></i> build/
│   │   ├── <i class="mdi mdi-folder-multiple"></i> Tailwind Css file
│   └── *.html
│   │    └── <i class="mdi mdi-file-multiple"></i> ALL HTML files
│   └── <i class="mdi mdi-file-multiple"></i> package-lock.json
│   └── <i class="mdi mdi-file-multiple"></i> package.json
│   └── <i class="mdi mdi-file-multiple"></i> tailwind.config.js
└── <i class="mdi mdi-folder-multiple"></i> Documentation/
        └── index.html - Index file for documentation.
</pre>
                            </div>
                        </div>
                    </section>
                    <section id="html">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">HTML</h5>
                            </div>
                            <div class="p-[26px] overflow-x-auto w-full">
                                <!-- HTML generated using hilite.me -->
                                <div style="background: #ffffff; overflow:auto;width:auto;padding:.2em 0px;">
                                    <pre style="margin: 0; line-height: 125%"><span style="color: #557799">&lt;!DOCTYPE html&gt;</span>
<span style="color: #007700">&lt;html&gt;</span>
<span style="color: #007700">&lt;head&gt;</span>
    <span style="color: #007700">&lt;meta</span> <span style="color: #0000CC">charset=</span><span style="background-color: #fff0f0">&quot;UTF-8&quot;</span><span style="color: #007700">&gt;</span>
    <span style="color: #007700">&lt;meta</span> <span style="color: #0000CC">name=</span><span style="background-color: #fff0f0">&quot;viewport&quot;</span> <span style="color: #0000CC">content=</span><span style="background-color: #fff0f0">&quot;width=device-width, initial-scale=1&quot;</span><span style="color: #007700">&gt;</span>
    <span style="color: #007700">&lt;meta</span> <span style="color: #0000CC">name=</span><span style="background-color: #fff0f0">&quot;description&quot;</span> <span style="color: #0000CC">content=</span><span style="background-color: #fff0f0">&quot;Tailwind CSS Multipurpose Landing Page Template&quot;</span> <span style="color: #007700">/&gt;</span>
    <span style="color: #007700">&lt;meta</span> <span style="color: #0000CC">name=</span><span style="background-color: #fff0f0">&quot;keywords&quot;</span> <span style="color: #0000CC">content=</span><span style="background-color: #fff0f0">&quot;&quot;</span> <span style="color: #007700">/&gt;</span>
    <span style="color: #007700">&lt;meta</span> <span style="color: #0000CC">name=</span><span style="background-color: #fff0f0">&quot;author&quot;</span> <span style="color: #0000CC">content=</span><span style="background-color: #fff0f0">&quot;ThemesBoss&quot;</span> <span style="color: #007700">/&gt;</span>

    <span style="color: #888888">&lt;!-- Site Title --&gt;</span>
    <span style="color: #007700">&lt;title&gt;</span>Landik - Tailwind CSS Multipurpose Landing Page Template<span style="color: #007700">&lt;/title&gt;</span>

    <span style="color: #888888">&lt;!-- Site favicon --&gt;</span>
    <span style="color: #007700">&lt;link</span> <span style="color: #0000CC">rel=</span><span style="background-color: #fff0f0">&quot;shortcut icon&quot;</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;assets/images/favicon.ico&quot;</span><span style="color: #007700">&gt;</span>

    <span style="color: #888888">&lt;!-- Custom  Css --&gt;</span>
    <span style="color: #007700">&lt;link</span> <span style="color: #0000CC">rel=</span><span style="background-color: #fff0f0">&quot;stylesheet&quot;</span> <span style="color: #0000CC">type=</span><span style="background-color: #fff0f0">&quot;text/css&quot;</span> <span style="color: #0000CC">href=</span><span style="background-color: #fff0f0">&quot;assets/css/style.css&quot;</span> <span style="color: #007700">/&gt;</span>

<span style="color: #007700">&lt;/head&gt;</span> 
<span style="color: #007700">&lt;body&gt;</span>
    <span style="color: #888888">&lt;!-- Header Start --&gt;</span>
    <span style="color: #007700">&lt;header&gt;</span>
        <span style="color: #007700">&lt;div</span> <span style="color: #0000CC">class=</span><span style="background-color: #fff0f0">&quot;******&quot;</span><span style="color: #007700">&gt;</span>
        ----------------
        <span style="color: #007700">&lt;/div&gt;</span>
    <span style="color: #007700">&lt;/header&gt;</span>
    <span style="color: #888888">&lt;!-- Header End --&gt;</span>

    <span style="color: #888888">&lt;!-- Start Footer --&gt;</span>
    <span style="color: #007700">&lt;footer</span> <span style="color: #0000CC">class=</span><span style="background-color: #fff0f0">&quot;******&quot;</span><span style="color: #007700">&gt;</span>
    ----------------
    <span style="color: #007700">&lt;/footer&gt;</span>
    <span style="color: #888888">&lt;!-- End Footer --&gt;</span>


    <span style="color: #888888">&lt;!-- All Javascript --&gt;</span>

    <span style="color: #888888">&lt;!-- Custom Js --&gt;</span>
    <span style="color: #007700">&lt;script </span><span style="color: #0000CC">src=</span><span style="background-color: #fff0f0">&quot;assets/js/custom.js&quot;</span><span style="color: #007700">&gt;&lt;/script&gt;</span>  
<span style="color: #007700">&lt;/body&gt;</span>
<span style="color: #007700">&lt;/html&gt;</span>
</pre>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section id="css">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">CSS</h5>
                            </div>
                            <div class="p-[26px]">
                                <p class="text-lg font-semibold">Landik Built with latest version of CSS3.</p>
                                <div class="overflow-x-auto w-full mt-4">
                                    <table class="w-full m-0 border whitespace-nowrap border-[#dee2e6]">
                                        <thead>
                                            <tr class="text-left">
                                                <th class="p-3 border border-[#dee2e6]">File Name</th>
                                                <th class="p-3 border border-[#dee2e6]">Details</th>
                                            </tr>
                                        </thead>
                                        <tbody>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">tailwind.css</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Tailwind CSS</td>
                                            </tr>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">swiper-bundle.min.css</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Swiper CSS</td>
                                            </tr>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">tobii.min.css</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Tobii CSS</td>
                                            </tr>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">accordion.min.css</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Accordion Css</td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section id="Javascript">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">Javascript</h5>
                            </div>
                            <div class="p-[26px]">
                                <p class="text-lg font-semibold">Landik Built with Javascript</p>
                                <div class="overflow-x-auto w-full mt-4">
                                    <table class="w-full m-0 border whitespace-nowrap border-[#dee2e6]">
                                        <thead>
                                            <tr class="text-left">
                                                <th class="p-3 border border-[#dee2e6]">File Name</th>
                                                <th class="p-3 border border-[#dee2e6]">Details</th>
                                            </tr>
                                        </thead>
                                        <tbody>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">js/accordion.min.js</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Accordion Js</td>
                                            </tr>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">js/swiper-bundle.min.js</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Swiper Js</td>
                                            </tr>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">js/tobii.min.js</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Tobii Js</td>
                                            </tr>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">js/vanilla-counter.js</code></td>
                                                <td class="p-3 border border-[#dee2e6]">Vanilla Counter</td>
                                            </tr>
                                            <tr>
                                                <td class="p-3 border border-[#dee2e6]"><code
                                                        class="text-[#e83e8c]">js/custom.js</code></td>
                                                <td class="p-3 border border-[#dee2e6]">All Custom js files</td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section id="features">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">Features</h5>
                            </div>
                            <div class="p-[26px]">
                                <p class="text-lg font-semibold">We are come with following features.</p>
                                <ul class="mt-3 list-inside list-disc space-y-2 text-muted">
                                    <li>Based on TailwindCSS <b>v3.2.4.</b></li>
                                    <li><b>4</b> Diffrent Landing Pages</li>
                                    <li>Built with HTML5 & CSS3</li>
                                    <li>Font Icons</li>
                                    <li>Google Fonts</li>
                                    <li>Easy to Customize</li>
                                    <li>Clean code</li>
                                    <li>Browser Compatibility</li>
                                    <li>Fully Customizable</li>
                                    <li>Modern Design</li>
                                    <li>And much more…</li>
                                </ul>
                            </div>
                        </div>
                    </section>
                    <section id="credit">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">Credit & Resources</h5>
                            </div>
                            <div class="p-[26px]">
                                <p class="text-lg font-semibold">We have used the following plugins.</p>
                                <ul class="mt-3 list-inside list-disc space-y-2 text-muted">
                                    <li><a href="https://tailwindcss.com/">Tailwind Css</a></li>
                                    <li><a href="https://github.com/olimsaidov/pixeden-stroke-7-icon">Pe 7s Icons</a>
                                    </li>
                                    <li><a href="https://materialdesignicons.com/">Materialdesign Icons</a></li>
                                    <li><a href="https://themify.me/themify-icons">Themify Icons</a></li>
                                    <li><a href="https://undraw.co/">Undraw Images</a></li>
                                    <li><a href="https://github.com/midzer/tobii">Tobii Lightbox</a></li>
                                    <li><a href="https://github.com/yunisdev/vanilla-counter">Vanilla Counter</a></li>
                                    <li><a href="https://swiperjs.com/">Swiper Js</a></li>
                                    <li><a href="https://github.com/michu2k/Accordion">Accordion Js</a></li>
                                    <li><a href="https://unsplash.com/">Unsplash</a></li>
                                    <li><a href="https://dribbble.com/">Dribbble</a></li>
                                    <li><a href="https://graphicburger.com/6-vintage-logo-badges-2/">Client Logo</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </section>
                    <section id="support">
                        <div class="border-2 border-[#f4f4f4] rounded-md mt-0">
                            <div class="p-[26px] border-b-2 border-[#f4f4f4]">
                                <h5 class="font-bold text-xl">Support</h5>
                            </div>
                            <div class="p-[26px]">
                                <p class="text-lg font-semibold">Thank you for become a part of us. If you have any
                                    query, suggestion and complain. Contact us anytime.</p>
                                <p class="text-custom mt-3 text-lg font-semibold">- support@themesboss.com</p>
                            </div>
                        </div>
                    </section>
                </section>

            </div>
        </div>
        <!-- </div> -->
    </section>
</template>