<script>
    import Typewriter from 'svelte-typewriter';
</script>

<div class="flex flex-col items-center pt-16 min-h-screen overflow-x-hidden">
    <div class="flex flex-col items-center px-4">
        <h1 class="text-8xl font-bold italic text-indigo-600">
            lnx
        </h1>
        <h3 class="text-2xl text-center font-bold">An adaptable search engine API.</h3>
    </div>
    <div class="flex flex-col items-center lg:items-start lg:flex-row md:justify-between xl:justify-center flex-wrap 2xl:px-16 my-4 lg:mt-24">
        <div class="flex flex-col items-center lg:items-start w-full lg:w-1/2 mt-12 lg:mt-24">
            <div class="text-2xl lg:text-6xl font-bold border-l-4 border-indigo-600 pt-1 pb-3 pl-4 w-4/5 lg:w-auto">
                Make it
                <div class="flex text-3xl lg:text-7xl ml-8">
                    >
                    <div class="italic text-indigo-600 ml-4">
                        <Typewriter loop interval={80}>
                            <span>lightning fast.</span>
                            <span>relevant.</span>
                            <span>typo tolerant.</span>
                            <span>search as you type.</span>
                            <span>your way.</span>
                        </Typewriter>
                    </div>
                </div>
            </div>
            <div class="flex justify-center lg:justify-start mt-8 lg:mt-16">
                <p class="text-3xl font-semibold text-center lg:text-left w-4/5 px-4 lg:px-0">
                    An open-source,
                    <span class="italic border-b-2 border-indigo-600">lightning-fast</span>
                    and <span class="italic border-b-2 border-indigo-600">typo tolerant</span>
                    search engine
                    empowering developers and users alike.
                </p>
            </div>
        </div>
        <div class="flex flex-col items-center bg-indigo-600 rounded-lg shadow-inner py-4 mx-4 text-white mt-8 lg:mt-0 w-9/12 lg:w-426">
            <div class="transform rotate-3 flex justify-center items-center h-24 bg-gray-900 rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <img class="w-12 h-12 mr-4" src="/love.svg" alt="">
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Community Driven</p>
                    <p class="text-sm lg:text-base">100% open-source, built for the community.</p>
                </div>
            </div>
            <div class="transform -rotate-3 flex justify-center items-center h-24 bg-gray-900 rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <img class="w-12 h-12 mr-4" src="/lightning.svg" alt="">
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Insanely Fast</p>
                    <p class="text-sm lg:text-base">Query millions of documents in milliseconds with
                        our fast-fuzzy system.</p>
                </div>
            </div>
            <div class="transform rotate-3 flex justify-around items-center h-24 bg-gray-900 rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <svg xmlns="http://www.w3.org/2000/svg" class="text-green-400 h-12 w-12 mr-4"
                     fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                          d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"/>
                </svg>
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Typo Tolerant</p>
                    <p class="text-sm lg:text-base">lnx provides fuzzy query systems to give you a
                        typo-tolerant query.</p>
                </div>
            </div>
            <div class="transform -rotate-3 flex justify-center items-center h-24 bg-gray-900 rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <svg xmlns="http://www.w3.org/2000/svg" class="text-white h-12 w-12 mr-4"
                     fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                          d="M3 5h12M9 3v2m1.048 9.5A18.022 18.022 0 016.412 9m6.088 9h7M11 21l5-10 5 10M12.751 5C11.783 10.77 8.07 15.61 3 18.129"/>
                </svg>
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Multi-Language</p>
                    <p class="text-sm lg:text-base">Currently lnx supports 17 latin languages.
                        Chinese, Japanese and Korean are planned.</p>
                </div>
            </div>
            <div class="flex justify-around items-center h-24 bg-gray-900 rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <a href="https://github.com/lnx-search/lnx"
                   class="cursor-pointer flex items-center justify-center hover:shadow-inner transform duration-200 text-center text-white text-base lg:text-2xl font-bold border-2 border-black bg-indigo-400 hover:bg-indigo-500 rounded-lg h-12 pb-1 px-4">
                    🕹️ Source
                </a>
                <a href="https://docs.lnx.rs"
                   class="cursor-pointer flex items-center justify-center hover:shadow-inner transform duration-200 text-center text-white text-base lg:text-2xl font-bold border-2 border-black bg-indigo-400 hover:bg-indigo-500 rounded-lg h-12 pb-1 px-4">
                    🚀 Get Started
                </a>
            </div>
        </div>
    </div>
    <div class="flex flex-col text-white bg-gray-900 2xl:px-16 mt-8 w-full">
        <div class="flex justify-around">
            <div class="transform lg:-translate-y-32 bg-indigo-600 rounded-lg p-4 mx-4 mt-8 lg:mt-0">
                <div class="flex flex-col">
                    <h3 class="text-white font-bold text-2xl">Quick start with docker</h3>
                    <p class="text-gray-100 text-lg mt-2">
                        Get started in seconds with our
                         <a
                            href="https://hub.docker.com/r/chillfish8/lnx"
                            class="italic font-semibold text-blue-300 border-b-2 border-transparent hover:border-blue-400 transition duration-200">
                            docker images
                        </a>, just run:
                    </p>
                    <p class="text-lg text-gray-200 bg-gray-800 rounded-lg px-4 py-1 mt-2">docker run -p "8000:8000" chillfish8/lnx:latest --host "0.0.0.0"</p>
                    <p class="text-gray-100 text-lg mt-2">
                        Once setup you can create indexes and start exploring everything<br/>
                        lnx has to offer with <a
                            href="https://docs.lnx.rs"
                            class="italic font-semibold text-blue-300 border-b-2 border-transparent hover:border-blue-400 transition duration-200">
                            the docs.
                        </a>
                    </p>
                </div>
            </div>
            <div class="hidden lg:block w-1/3"></div>
        </div>
    </div>
    <div class="flex flex-col items-center lg:items-start lg:flex-row-reverse md:justify-between xl:justify-center flex-wrap text-white bg-gray-900 2xl:px-16 w-full">
        <div class="transform lg:-translate-y-48 flex flex-col w-5/6 lg:w-2/5 mt-12 lg:ml-48">
            <div class="flex">
                <h3 class="text-2xl lg:text-5xl 2xl:text-6xl font-bold mb-6 border-b-4 border-indigo-600">The query kinds</h3>
            </div>
            <div class="flex flex-col mt-4 border-l-2 border-indigo-600">
                <h3 class="text-white font-bold text-2xl pl-2">
                    The <span class="italic text-red-400">"normal"</span> query
                </h3>
                <p class="text-gray-500 text-lg lg:text-xl font-semibold pl-2 pb-2">
                    This mode exposes the
                    <a
                            href="https://docs.rs/tantivy/0.16.0/tantivy/query/struct.QueryParser.html"
                            class="text-blue-400 border-b-2 border-transparent hover:border-blue-400 transition duration-200">
                        Tantivy query parser
                    </a>
                    which gives you a powerful query language for searching things like logs.
                </p>
            </div>
            <div class="flex flex-col mt-4 border-l-2 border-indigo-600">
                <h3 class="text-white font-bold text-2xl pl-2">
                    The <span class="italic text-red-400">"fuzzy"</span> query
                </h3>
                <p class="text-gray-500 text-lg lg:text-xl font-semibold pl-2 pb-2">
                    This mode uses the traditional
                    <a
                            href="https://en.wikipedia.org/wiki/Levenshtein_distance"
                            class="text-blue-400 border-b-2 border-transparent hover:border-blue-400 transition duration-200">
                         Levenshtein distance
                    </a>
                      to find close
                    matches giving you typo-tolerance with your queries.
                </p>
            </div>
            <div class="flex flex-col mt-4 border-l-2 border-indigo-600">
                <h3 class="text-white font-bold text-2xl pl-2">
                    The <span class="italic text-red-400">"more-like-this"</span> query
                </h3>
                <p class="text-gray-500 text-lg lg:text-xl font-semibold pl-2 pb-2">
                    Get similar documents to a reference document, great for e-commerce
                    or e-readers.
                </p>
            </div>
            <div class="flex flex-col mt-4 border-l-2 border-indigo-600">
                <h3 class="text-white font-bold text-2xl pl-2">
                    The <span class="italic text-red-400">"fast-fuzzy"</span> query
                </h3>
                <p class="text-gray-500 text-lg lg:text-xl font-semibold pl-2 pb-2">
                    The fast-fuzzy mode is a implementation of the
                    <a
                            href="https://towardsdatascience.com/symspellcompound-10ec8f467c9b"
                            class="text-blue-400 border-b-2 border-transparent hover:border-blue-400 transition duration-200">
                        symspell algorithm
                    </a>
                    which provides spell corrections via pre-computation.
                    This is the secret sauce behind being able to blow other engines
                    out of the water when it comes to fuzzy searching.
                </p>
            </div>
            <!-- <div class="flex mt-32">
                <h3 class="text-2xl lg:text-5xl 2xl:text-6xl font-bold mb-6 border-b-4 border-indigo-600">
                    Try it out for yourself
                </h3>
            </div>  -->
        </div>
        <div class="flex flex-col items-center bg-indigo-600 rounded-lg shadow-inner py-4 mx-4 text-gray-900 mt-8 lg:mt-0 w-9/12 lg:w-426">
            <div class="transform -rotate-3 flex justify-center items-center h-24 bg-white rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <svg xmlns="http://www.w3.org/2000/svg" class="text-blue-900 rounded rounded-lg bg-blue-400 border-2 border-blue-600 shadow-inner w-12 h-12 p-2 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 4h13M3 8h9m-9 4h9m5-4v12m0 0l-4-4m4 4l4-4" />
                </svg>
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Sorting By Field</p>
                    <p class="text-sm lg:text-base">Results can be sorted by any fast-field quickly and easily.</p>
                </div>
            </div>
            <div class="transform rotate-3 flex justify-center items-center h-24 bg-white rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <svg xmlns="http://www.w3.org/2000/svg" class="text-green-900 rounded-lg bg-green-300 border-2 border-green-500 shadow-inner w-12 h-12 p-2 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" />
                </svg>
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Stop Words</p>
                    <p class="text-sm lg:text-base">
                        With a pre-made set, stop words can be removed to boost
                        relevancy in queries.
                    </p>
                </div>
            </div>
            <div class="transform -rotate-3 flex justify-center items-center h-24 bg-white rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <svg xmlns="http://www.w3.org/2000/svg" class="text-red-900 rounded-lg bg-red-400 border-2 border-red-600 shadow-inner w-12 h-12 p-2 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 7a2 2 0 012 2m4 0a6 6 0 01-7.743 5.743L11 17H9v2H7v2H4a1 1 0 01-1-1v-2.586a1 1 0 01.293-.707l5.964-5.964A6 6 0 1121 9z" />
                </svg>
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Token Bearer Authorization</p>
                    <p class="text-sm lg:text-base">
                        Secure your system giving permissions based access to specific users.
                    </p>
                </div>
            </div>
            <div class="transform rotate-3 flex justify-center items-center h-24 bg-white rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <svg xmlns="http://www.w3.org/2000/svg" class="text-purple-900 rounded-lg bg-purple-400 border-2 border-purple-600 shadow-inner w-12 h-12 p-2 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
                </svg>
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Boost Fields</p>
                    <p class="text-sm lg:text-base">
                        Each fields can be individually adjusted to give the best
                        searching experience.
                    </p>
                </div>
            </div>
            <div class="transform -rotate-3 flex justify-center items-center h-24 bg-white rounded-lg shadow-md my-4 p-4 w-80 lg:w-28">
                <svg xmlns="http://www.w3.org/2000/svg" class="text-yellow-900 rounded-lg bg-yellow-400 border-2 border-yellow-600 shadow-inner w-12 h-12 p-2 mr-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                </svg>
                <div class="flex flex-col w-3/4">
                    <p class="text-base lg:text-xl font-bold italic">Fast-Fuzzy Pre-Computation</p>
                    <p class="text-sm lg:text-base">
                        This feature uses pre-computation to boost fuzzy query performance by over
                        <span class="font-bold italic">10x</span>.
                    </p>
                </div>
            </div>
        </div>
        <div class="flex flex-wrap items-center justify-evenly border-t-2 border-gray-600 text-gray-400 mt-32 py-8 w-full">
            <p>© 2021 lnx search.</p>
            <a href="https://docs.lnx.rs">Docs</a>
            <a href="https://github.com/lnx-search/lnx/discussions">FAQ</a>
            <a href="https://hub.docker.com/r/chillfish8/lnx">Docker Images</a>
            <a href="https://github.com/lnx-search/lnx">GitHub</a>
        </div>
    </div>
</div>
