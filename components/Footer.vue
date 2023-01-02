<template>
  <footer aria-labelledby="footer-heading" class="flex flex-col flex-1">
    <h2 id="footer-heading" class="sr-only">Footer</h2>
    <div class="flex md:items-center justify-between mt-6 pt-6 md:mt-12 md:pt-12 border-t border-zinc-700">
      <div class="flex items-center space-x-2">
        <FooterLink
          label="Sete Três"
          url="https://setetr.es"
        >
          <svg class="w-4 h-4" viewBox="0 0 16 16" fill="currentColor">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M2 0H3V3H5V4H3H2V0ZM6 2V3H5V2H6ZM10 3H8V0H7V1H6V2H7V5H6V6H3V7H2V8H1V9H2V10H1V11H2V14H3V11H4V10H3V9H4V8H3V7H6V6H7V5H8V4H10V3ZM11 2V3H10V2H11ZM12 5V2H11V1H12V0H13V5H12ZM11 6V5H12V6H11ZM11 7H10H9V6H10H11V7ZM12 8H11V7H12V8ZM13 9V8H12V9V11H11V10H10V9H8V8H7V16H8V10H10V11H11V12H12V13H13V9ZM3 8V9H2V8H3ZM3 10H2V11H3V10ZM15 6H14V7H15V6Z"/>
          </svg>
        </FooterLink>
        <span class="hidden sm:inline text-xs text-zinc-400 uppercase">
          Since 2008 — Media, Unlimited.
        </span>
      </div>
      <div class="flex items-center justify-start sm:justify-end space-x-2">
        <FooterLink
          label="Apple Music"
          url="https://music.apple.com/br/artist/xxxxxxxooo/1513745230"
        >
          <svg class="h-4 w-4" fill="currentColor" viewBox="0 0 384 512">
            <path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/>
          </svg>
        </FooterLink>
        <FooterLink
          label="Bandcamp"
          url="https://xxxxxxxooo.bandcamp.com"
        >
          <svg class="h-4 w-4" fill="currentColor" viewBox="0 0 512 512">
            <path d="M256,8C119,8,8,119,8,256S119,504,256,504,504,393,504,256,393,8,256,8Zm48.2,326.1h-181L207.9,178h181Z"/>
          </svg>
        </FooterLink>
        <FooterLink
          label="Deezer"
          url="https://deezer.com/br/artist/94957922"
        >
          <svg class="h-4 w-4" fill="currentColor" viewBox="0 0 576 512">
            <path d="M451.46,244.71H576V172H451.46Zm0-173.89v72.67H576V70.82Zm0,275.06H576V273.2H451.46ZM0,447.09H124.54V374.42H0Zm150.47,0H275V374.42H150.47Zm150.52,0H425.53V374.42H301Zm150.47,0H576V374.42H451.46ZM301,345.88H425.53V273.2H301Zm-150.52,0H275V273.2H150.47Zm0-101.17H275V172H150.47Z"/>
          </svg>
        </FooterLink>
        <FooterLink
          label="Spotify"
          url="https://open.spotify.com/artist/4jTVrvdD8pkTxnc9bRPcwU"
        >
          <svg class="h-4 w-4" fill="currentColor" viewBox="0 0 496 512">
            <path d="M248 8C111.1 8 0 119.1 0 256s111.1 248 248 248 248-111.1 248-248S384.9 8 248 8zm100.7 364.9c-4.2 0-6.8-1.3-10.7-3.6-62.4-37.6-135-39.2-206.7-24.5-3.9 1-9 2.6-11.9 2.6-9.7 0-15.8-7.7-15.8-15.8 0-10.3 6.1-15.2 13.6-16.8 81.9-18.1 165.6-16.5 237 26.2 6.1 3.9 9.7 7.4 9.7 16.5s-7.1 15.4-15.2 15.4zm26.9-65.6c-5.2 0-8.7-2.3-12.3-4.2-62.5-37-155.7-51.9-238.6-29.4-4.8 1.3-7.4 2.6-11.9 2.6-10.7 0-19.4-8.7-19.4-19.4s5.2-17.8 15.5-20.7c27.8-7.8 56.2-13.6 97.8-13.6 64.9 0 127.6 16.1 177 45.5 8.1 4.8 11.3 11 11.3 19.7-.1 10.8-8.5 19.5-19.4 19.5zm31-76.2c-5.2 0-8.4-1.3-12.9-3.9-71.2-42.5-198.5-52.7-280.9-29.7-3.6 1-8.1 2.6-12.9 2.6-13.2 0-23.3-10.3-23.3-23.6 0-13.6 8.4-21.3 17.4-23.9 35.2-10.3 74.6-15.2 117.5-15.2 73 0 149.5 15.2 205.4 47.8 7.8 4.5 12.9 10.7 12.9 22.6 0 13.6-11 23.3-23.2 23.3z"/>
          </svg>
        </FooterLink>
        <FooterLink
          label="Tidal"
          url="https://tidal.com/browse/artist/19639139"
        >
          <svg class="h-4 w-4" fill="currentColor" viewBox="0 0 640 512">
            <path d="M426.25 148.858 320.003 255.75 213.75 148.858 320.003 42 426.25 148.858ZM426.25 362.622 320.003 469.5 213.75 362.622 320.003 255.75 426.25 362.622ZM213.75 148.862 106.872 255.75 0 148.862 106.872 42 213.75 148.862ZM640 148.862 533.131 255.75 426.25 148.862 533.131 42 640 148.862Z"/>
          </svg>
        </FooterLink>
        <FooterLink
          label="YouTube"
          url="https://youtube.com/setetres"
        >
          <svg class="h-4 w-4" fill="currentColor" viewBox="0 0 512 512">
            <path d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z"/>
          </svg>
        </FooterLink>
      </div>
    </div>
  </footer>
</template>
