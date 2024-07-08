<script setup></script>

<template>
  <div
    class="flex gap-2 flex-col justify-items-center items-center text-center"
  >
    <h1 class="text-primary text-lg font-medium leading-h1-height text-h1-size">
      Pricing Plans
    </h1>
    <div class="leading-text-height text-textColor text-text-size">
      <p>
        All plans include 40+ advanced tools and features to boost your product.
      </p>
      <p>Choose the best plan to fit your needs.</p>
    </div>
    <div class="flex justify-items-center ml-260px">
      <svg
        class="mt-15px"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M18 6.75003C18.4142 6.75003 18.75 6.41424 18.75 6.00003C18.75 5.58582 18.4142 5.25003 18 5.25003V6.75003ZM9 19L8.46967 19.5304C8.68417 19.7449 9.00676 19.809 9.28701 19.6929C9.56727 19.5769 9.75 19.3034 9.75 19H9ZM5.53033 14.4697C5.23744 14.1768 4.76256 14.1768 4.46967 14.4697C4.17678 14.7626 4.17678 15.2375 4.46967 15.5304L5.53033 14.4697ZM13.5303 15.5304C13.8232 15.2375 13.8232 14.7626 13.5303 14.4697C13.2374 14.1768 12.7626 14.1768 12.4697 14.4697L13.5303 15.5304ZM8.46967 18.4697C8.17678 18.7626 8.17678 19.2375 8.46967 19.5304C8.76256 19.8233 9.23744 19.8233 9.53033 19.5304L8.46967 18.4697ZM18 5.25003H12V6.75003H18V5.25003ZM12 5.25003C9.92893 5.25003 8.25 6.92896 8.25 9.00003H9.75C9.75 7.75739 10.7574 6.75003 12 6.75003V5.25003ZM8.25 9.00003V19H9.75V9.00003H8.25ZM9.53033 18.4697L5.53033 14.4697L4.46967 15.5304L8.46967 19.5304L9.53033 18.4697ZM12.4697 14.4697L8.46967 18.4697L9.53033 19.5304L13.5303 15.5304L12.4697 14.4697Z"
          fill="#2F2B3D"
          fill-opacity="0.4"
        />
      </svg>
      <p
        class="text-menuActiveLight bg-menuActiveBackgroundDark my-7.5px px-2.5 py-0.5 rounded-lg"
      >
        Save up to 10%
      </p>
    </div>
    <div
      class="flex gap-2 font-medium text-text-size text-textColor items-center"
    >
      <p class="py-2">Monthly</p>

      <div>
        <svg
          width="48"
          height="36"
          viewBox="0 0 48 36"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <g filter="url(#filter0_i_60_1382)">
            <path
              d="M9 18C9 13.0295 13.0294 9.00003 18 9.00003H30C34.9706 9.00003 39 13.0295 39 18C39 22.9706 34.9706 27 30 27H18C13.0294 27 9 22.9706 9 18Z"
              fill="#2F2B3D"
              fill-opacity="0.1"
            />
          </g>
          <g filter="url(#filter1_d_60_1382)">
            <circle cx="18" cy="18" r="7" fill="white" />
          </g>
          <defs>
            <filter
              id="filter0_i_60_1382"
              x="9"
              y="9.00003"
              width="30"
              height="18"
              filterUnits="userSpaceOnUse"
              color-interpolation-filters="sRGB"
            >
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feBlend
                mode="normal"
                in="SourceGraphic"
                in2="BackgroundImageFix"
                result="shape"
              />
              <feColorMatrix
                in="SourceAlpha"
                type="matrix"
                values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha"
              />
              <feOffset />
              <feGaussianBlur stdDeviation="2" />
              <feComposite
                in2="hardAlpha"
                operator="arithmetic"
                k2="-1"
                k3="1"
              />
              <feColorMatrix
                type="matrix"
                values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.16 0"
              />
              <feBlend
                mode="normal"
                in2="shape"
                result="effect1_innerShadow_60_1382"
              />
            </filter>
            <filter
              id="filter1_d_60_1382"
              x="5"
              y="6.00003"
              width="26"
              height="26"
              filterUnits="userSpaceOnUse"
              color-interpolation-filters="sRGB"
            >
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix
                in="SourceAlpha"
                type="matrix"
                values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha"
              />
              <feOffset dy="1" />
              <feGaussianBlur stdDeviation="3" />
              <feColorMatrix
                type="matrix"
                values="0 0 0 0 0.184314 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 0.1 0"
              />
              <feBlend
                mode="normal"
                in2="BackgroundImageFix"
                result="effect1_dropShadow_60_1382"
              />
              <feBlend
                mode="normal"
                in="SourceGraphic"
                in2="effect1_dropShadow_60_1382"
                result="shape"
              />
            </filter>
          </defs>
        </svg>
      </div>

      <p class="py-2">Annually</p>
    </div>
  </div>
</template>

<style scoped></style>
