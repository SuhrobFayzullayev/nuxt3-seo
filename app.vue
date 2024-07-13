<script setup lang="ts">
useSeoMeta({
  title: "TITLE",
  description: "DESCRIPTION",
  author: "example.com",

  // application
  applicationName: "NAME",

  // og
  ogTitle: "TITLE",
  ogDescription: "DESCRIPTION",
  ogType: "website", // "website" | "article" | "book" | "profile" | "music.song" | "music.album" | "music.playlist" | "music.radio_status" | "video.movie" | "video.episode" | "video.tv_show" | "video.other"
  ogUrl: "ARTICLE_LINK",
  ogSiteName: "SITE_NAME",
  // og locale
  ogLocale: "en_US",
  ogLocaleAlternate: ["ru_RU", "uz_UZ"],
  // og image
  ogImage: {
    width: 300,
    height: 200,
    url: "IMAGE_URL",
    secureUrl: "IMAGE_URL",
    alt: "ARTICLE_TITLE",
    type: "image/png", // 'image/png' | 'image/jpeg' | 'image/gif'
  },
  // og audio
  ogAudioType: "audio/mpeg", // audio/mpeg" | "audio/ogg" | "audio/wav
  ogAudio: {
    url: "AUDIO_URL",
    secureUrl: "AUDIO_URL",
  },
  // og video
  ogVideo: {
    url: "VIDEO_URL",
    secureUrl: "VIDEO_URL",
    type: "video/mp4", // "application/x-shockwave-flash" | "video/mp4";
    width: 300,
    height: 200,
    alt: "ARTICLE_TILE",
  },

  // twitter
  twitterTitle: "TITLE",
  twitterDescription: "DESCRIPTION",
  twitterCard: "summary_large_image", // "summary_large_image" | "summary" | "app" | "player"
  twitterCreator: "@TWITTER_USER_NAME",
  twitterSite: "@TWITTER_USER_NAME",
  // twitter image
  twitterImage: {
    url: "IMAGE_URL",
    alt: "ARTICLE_TITLE",
  },
  // twitter player (for iframe)
  twitterPlayerStream: "example.mp4", // video type
  twitterPlayer: "example.mp4", // video type
  twitterPlayerWidth: 300,
  twitterPlayerHeight: 200,
  // twitter mobile app 'if you have MOBILE APP in App Store or Google Play'
  twitterAppIdGoogleplay: "1",
  twitterAppIdIpad: "1",
  twitterAppIdIphone: "1",
  twitterAppNameGoogleplay: "NAME",
  twitterAppNameIpad: "NAME",
  twitterAppNameIphone: "NAME",
  twitterAppUrlGoogleplay: "URL",
  twitterAppUrlIpad: "URL",
  twitterAppUrlIphone: "URL",

  // article
  articleSection: "NEWS",
  articleTag: ["NEWS", "SPORT"],
  articlePublishedTime: "1970-01-01T00:00:00.000Z",
  articleModifiedTime: "1971-01-01T00:00:00.000Z",
  articleAuthor: ["name1", "name2"],

  // profile
  profileFirstName: "NAME",
  profileLastName: "NAME",
  profileUsername: "@username",
  profileGender: "male",

  // book
  bookAuthor: ["example.com/books/authos/1", "example.com/books/authos/2"],
  bookTag: ["JS", "Python"],
  bookReleaseDate: "1970-01-01T00:00:00.000Z",

  // facebook
  fbAppId: "0",

  // apple web app
  appleMobileWebAppTitle: "TITLE",
  appleMobileWebAppCapable: "yes",

  // mobile web app
  mobileWebAppCapable: "yes",

  // itunes
  appleItunesApp: {
    appId: "0",
  },
});
useHead({
  link: [
    {
      rel: "apple-touch-icon",
      sizes: "NUMBERxNUMBER", // 16x16
      href: "example.com/image",
    },
    {
      rel: "icon",
      type: "image/png", // 'image/avif', 'image/bmp', 'image/gif', 'image/jpeg', 'image/svg+xml', 'image/tiff', 'image/vnd.microsoft.icon', 'image/webp'
      sizes: "NUMBERxNUMBER", // 16x16
      href: "example.com/image",
    },
    {
      rel: "icon",
      type: "image/png", // 'image/avif', 'image/bmp', 'image/gif', 'image/jpeg', 'image/svg+xml', 'image/tiff', 'image/vnd.microsoft.icon', 'image/webp'
      sizes: "NUMBERxNUMBER", // 32x32
      href: "example.com/image",
    },
  ],
});
</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
