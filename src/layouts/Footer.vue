<script setup></script>

<template>
    <!-- Footer Start -->
    <footer class="bg-theme-dark-blue py-10">
        <div class="container mx-auto px-5">
            <div class="grid md:grid-cols-2">
                <div class="flex flex-col md:flex-row md:space-x-12 items-center">
                    <div class="mb-10 md:mb-0">
                        <img src="/images/logo-bookmark-white.svg" alt="Logo" />
                    </div>
                    <ul class="flex flex-col md:flex-row space-y-5 md:space-y-0 md:space-x-8 text-xs text-center md:text-left font-theme-heading">
                        <li class="uppercase text-white hover:text-theme-secondary transition duration-200">
                            <a href="#features" v-smooth-scroll>Features</a>
                        </li>
                        <li class="uppercase text-white hover:text-theme-secondary transition duration-200">
                            <a href="#faq" v-smooth-scroll>FAQ</a>
                        </li>
                        <li class="uppercase text-white hover:text-theme-secondary transition duration-200">
                            <a href="#download-section" v-smooth-scroll>Download</a>
                        </li>
                    </ul>
                </div>
                <div class="md:place-self-end place-self-center mt-10 md:mt-0">
                    <ul class="flex space-x-8 items-center">
                        <li>
                            <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-facebook text-white hover:text-theme-secondary transition duration-200 cursor-pointer" viewBox="0 0 16 16">
                                <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z" />
                            </svg>
                        </li>
                        <li>
                            <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-twitter text-white hover:text-theme-secondary transition duration-200 cursor-pointer" viewBox="0 0 16 16">
                                <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z" />
                            </svg>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
    <!-- Footer End -->
</template>
