<script>
import { mapState } from "vuex";

export default {
  data: () => {
    return {
      // @todo
    };
  },
  computed: {
    ...mapState(["aboutMe"]),
  },
};
</script>

<template>
  <div>
  
    <div data-v-38d755c4="" class="block sm:flex gap-0 sm:gap-10 mt-14">
      <div data-v-38d755c4="" class="w-full sm:w-1/3 text-left">
      <div data-v-38d755c4="" class="mb-7">
        <p data-v-38d755c4="" class="
            font-general-medium
            text-primary-dark
            dark:text-primary-light
            text-2xl
            font-bold
            mb-7
            ">
            About 
          </p>
          <p data-v-38d755c4="" class="
              font-general-regular
              text-primary-dark
              dark:text-ternary-light
            ">
             Sama Soltani was born in 1986, in Kermanshah, Iran
              and began painting at the tender age of five.
            </p>
             
              </div> 
              <div data-v-38d755c4="" class="mb-7">
                <p data-v-38d755c4="" class="
              font-general-medium
              text-2xl text-ternary-dark
              dark:text-ternary-light
              mb-2
            ">
          Education
          </p> <p data-v-38d755c4="" class="
              font-general-regular
              text-primary-dark
              dark:text-ternary-light
            ">
            Master of Fine Art,
            Anglia Ruskin University, 2013
            Bachelors Degree in Painting,
            Tehran Art University, 2012
          </p></div> <div data-v-38d755c4="" class="mb-7"><p data-v-38d755c4="" class="
              font-general-medium
              text-2xl text-ternary-dark
              dark:text-ternary-light
              mb-2
            ">
            Workshops
          </p> <p data-v-38d755c4="" class="
              font-general-regular
              text-primary-dark
              dark:text-ternary-light
            ">
            Norouz: Celebrating Spring at Persian New Year
            Victoria and Albert Museum March 2015
          </p></div> <div data-v-38d755c4=""><p data-v-38d755c4="" class="
              font-general-medium
              text-2xl text-ternary-dark
              dark:text-ternary-light
              mb-2
            ">
            Share This
          </p> <div data-v-38d755c4="" class="flex items-center gap-3 mt-5"><a data-v-38d755c4="" href="https://twitter.com/realstoman" target="__blank" aria-label="Share Project" class="
                bg-ternary-light
                dark:bg-ternary-dark
                text-gray-400
                hover:text-primary-dark
                dark:hover:text-primary-light
                p-2
                rounded-lg
                shadow-sm
                duration-500
              "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-twitter w-4 lg:w-5 h-4 lg:h-5" data-v-38d755c4=""><path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"></path></svg></a><a data-v-38d755c4="" href="https://instagram.com/realstoman" target="__blank" aria-label="Share Project" class="
                bg-ternary-light
                dark:bg-ternary-dark
                text-gray-400
                hover:text-primary-dark
                dark:hover:text-primary-light
                p-2
                rounded-lg
                shadow-sm
                duration-500
              "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-instagram w-4 lg:w-5 h-4 lg:h-5" data-v-38d755c4=""><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg></a><a data-v-38d755c4="" href="https://facebook.com/" target="__blank" aria-label="Share Project" class="
                bg-ternary-light
                dark:bg-ternary-dark
                text-gray-400
                hover:text-primary-dark
                dark:hover:text-primary-light
                p-2
                rounded-lg
                shadow-sm
                duration-500
              "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-facebook w-4 lg:w-5 h-4 lg:h-5" data-v-38d755c4=""><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg></a><a data-v-38d755c4="" href="https://linkedin.com/" target="__blank" aria-label="Share Project" class="
                bg-ternary-light
                dark:bg-ternary-dark
                text-gray-400
                hover:text-primary-dark
                dark:hover:text-primary-light
                p-2
                rounded-lg
                shadow-sm
                duration-500
              "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-linkedin w-4 lg:w-5 h-4 lg:h-5" data-v-38d755c4=""><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg></a><a data-v-38d755c4="" href="https://www.youtube.com/c/StomanStudio" target="__blank" aria-label="Share Project" class="
                bg-ternary-light
                dark:bg-ternary-dark
                text-gray-400
                hover:text-primary-dark
                dark:hover:text-primary-light
                p-2
                rounded-lg
                shadow-sm
                duration-500
              "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-youtube w-4 lg:w-5 h-4 lg:h-5" data-v-38d755c4=""><path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z"></path><polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"></polygon></svg></a></div></div></div> <div data-v-38d755c4="" class="w-full sm:w-2/3 text-left mt-10 sm:mt-0">
            <p data-v-38d755c4="" class="
            font-general-medium
            text-primary-dark
            dark:text-primary-light
            text-2xl
            font-bold
            mb-7
          ">
          Exhibitions
              </p> <p data-v-38d755c4="" class="
            font-general-regular
            mb-5
            text-lg text-ternary-dark
            dark:text-ternary-light
          ">
          Phenomena Solo Exhibition The Locker,  August 2018 05 Artists Group Exhibition Maker's Gallery Cambridge June 2018 Encounters with Persian Art, Verse & Music Solo Art Exhibitor Fitzwilliam College Cambridge University May 2018 Ode to Peace Solo Exhibition Cadogan Hall London, UK January 2016 Parallels Solo Exhibition Old Lab Newnham College, Cambridge University Cambridge, UK November 2015 In the Dark Room of Shanameh Solo Exhibition Candid Arts Trust London, UK  May 2015 Shanameh Forever Group Exhibition The Shanameh Centre Pembroke College, Cambridge University Cambridge, UK May 2014 What's Dot to Like Solo Exhibition Arts Picture House Cambridge, UK January - Febuary 2014 Imagining the Shahnameh in the 21st Century Group Exhibition Festival of Ideas The West Road Concert Hall, Cambridge University Cambridge, UK October 2013 Anglia Ruskin Gallery Group Exhibition Cambridge, UK September 2013 616 Gallery Cambridge, UK May 2013 Group Exhibition supported by British Council Coventry, UK June 2004 Group Exhibition supported by British Council Tehran, UK July 2004        </p><p data-v-38d755c4="" class="
            font-general-regular
            mb-5
            text-lg text-ternary-dark
            dark:text-ternary-light
          ">
          The paintings in this collection are my interpretation of the poems from the Shahnameh.
        </p>
             <p data-v-38d755c4="" class="
            font-general-medium
            text-primary-dark
            dark:text-primary-light
            text-2xl
            font-bold
            mb-7
          ">
          Acheivements
              </p> <p data-v-38d755c4="" class="
            font-general-regular
            mb-5
            text-lg text-ternary-dark
            dark:text-ternary-light
          ">
              Illustrated book entitled 'Shahnameh'
              Calligraphist: Fariba Maghsoudi
              Published by Rishe Publisher 2012
              Attendance at Middle East Art Workshop
              Agha Khan University 2012
              Illustration of Prayers of Muhammad (Peace be upon him)
              Published by Kaveh Publisher 2011 Illumination of
              Ali Khayyam Poems Published by Ali Publisher 2011 Researcher for Caligraphy Workshop Pakistan and Iran Art Universities 2008-9 Winner:Best Painter Seventh Islamic Art Festival Tehran, Iran 2008 Translated the book: Islamic Pattern written by Eva Willson
              Published by Soha Publisher 2008 Youngest Featured Painter Sixth Islamic Art Festival Tehran, Iran 2006 Featured writer for three different Iranian nation-wide newspapers 2004-06 1st School Books Illustration Festival Tehran, Iran 2005 Voted
              Best Art Student Visual Art School Tehran, Iran 2002, 2003, 2004</p>
        </div></div>
  </div>
  
</template>
