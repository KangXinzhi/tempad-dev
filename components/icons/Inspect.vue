<script setup lang="ts">
import { ui } from '@/ui/figma'
</script>

<template>
  <svg
    v-if="ui.isUi3"
    class="tp-icon"
    xmlns="http://www.w3.org/2000/svg"
    width="32"
    height="32"
    fill="none"
    viewBox="-4 -4 32 32"
  >
    <mask
      id="fpl-icon-24-move-a"
      width="17"
      height="17"
      x="4"
      y="4"
      fill="#000"
      maskUnits="userSpaceOnUse"
    >
      <path fill="#fff" d="M4 4h17v17H4z"></path>
      <path
        fill-rule="evenodd"
        d="M19.294 12.063a1 1 0 0 0 .072-1.887l-13-5.107a1 1 0 0 0-1.297 1.297l5.107 13a1 1 0 0 0 1.887-.072l1.701-5.53 5.53-1.701Z"
        clip-rule="evenodd"
      ></path>
    </mask>
    <path
      fill="currentColor"
      d="M19.294 12.063 19 11.107l.294.956Zm.072-1.887.365-.93-.365.93Zm-13-5.107.365-.93-.365.93ZM5.069 6.366l-.93.365.93-.365Zm5.107 13-.93.365.93-.365Zm1.887-.072L11.107 19l.956.294Zm1.701-5.53-.294-.955a1 1 0 0 0-.661.661l.955.294ZM19 11.107l.588 1.912a2 2 0 0 0 1.41-1.836L19 11.107Zm0 0 1.999.076a2 2 0 0 0-1.268-1.937L19 11.107ZM6 6l13 5.107.731-1.861-13-5.107L6 6Zm0 0 .731-1.861a2 2 0 0 0-2.145.447L6 6Zm0 0L4.586 4.586a2 2 0 0 0-.448 2.145L6 6Zm5.107 13L6 6l-1.862.731 5.108 13L11.107 19Zm0 0-1.861.731A2 2 0 0 0 11.183 21l-.076-2Zm0 0 .076 1.999a2 2 0 0 0 1.836-1.41L11.107 19Zm1.702-5.53L11.107 19l1.912.588 1.701-5.53-1.911-.588ZM19 11.107l-5.53 1.702.588 1.911 5.53-1.701L19 11.107Z"
      mask="url(#fpl-icon-24-move-a)"
    ></path>
  </svg>
  <svg
    v-else
    class="tp-icon"
    xmlns="http://www.w3.org/2000/svg"
    width="36"
    height="36"
    viewBox="-6 -6 36 36"
  >
    <path
      fill="currentColor"
      fill-opacity="1"
      fill-rule="evenodd"
      stroke="none"
      d="M4.5 4H4v15h5v-1H5V5h13v4h1V4H4.5zm17.93 11.449L17 16.999l-1.551 5.43-.45 1.57-.606-1.516-4.88-12.2L9 9l1.282.513 12.201 4.88L24 15l-1.57.449zm-6.392 1.276-1.196 4.188-4.047-10.118 10.118 4.047-4.188 1.196-.534.153-.153.534z"
    ></path>
  </svg>
</template>
