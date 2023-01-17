<script setup lang="ts">
const LIST = [
  {
    title: "Track company-wide progress",
    paragraph:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, aut sapiente, aliquam distinctio harum quidem, nulla cupiditate officia magni necessitatibus ducimus. Porro sit consequuntur incidunt aliquid, neque tenetur maiores deleniti?",
  },
  {
    title: "Track company-wide progress",
    paragraph:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, aut sapiente, aliquam distinctio harum quidem, nulla cupiditate officia magni necessitatibus ducimus. Porro sit consequuntur incidunt aliquid, neque tenetur maiores deleniti?",
  },
  {
    title: "Track company-wide progress",
    paragraph:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, aut sapiente, aliquam distinctio harum quidem, nulla cupiditate officia magni necessitatibus ducimus. Porro sit consequuntur incidunt aliquid, neque tenetur maiores deleniti?",
  },
];
</script>

<template>
  <!-- Features Section -->
  <section id="features">
    <!-- Flex container -->
    <div
      class="container mx-auto mt-10 flex flex-col items-center space-y-12 px-4 md:flex-row md:items-baseline md:space-y-0"
    >
      <!-- What's Different -->
      <div class="flex flex-col space-y-12 md:w-1/2">
        <h2 class="max-w-md text-center text-4xl font-bold md:text-left">
          What's different about Manage?
        </h2>
        <p class="max-w-sm text-center text-gray-600 md:text-left">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae
          voluptas laborum at cum doloribus totam sint voluptates incidunt quae
          molestias labore eius nisi laboriosam error rem, cumque animi ad iste!
        </p>
      </div>

      <!-- Numbered List -->
      <ul class="flex flex-col space-y-8 md:w-1/2">
        <!-- List Item-->
        <li
          v-for="(item, i) in LIST"
          :key="i"
          class="flex flex-col space-y-3 md:flex-row md:space-y-0 md:space-x-6"
        >
          <!-- Heading -->
          <div class="rounded-l-full bg-orange-200 md:bg-transparent">
            <div class="flex items-center space-x-2">
              <div
                class="rounded-full bg-orange-600 px-4 py-2 text-white md:py-1"
              >
                {{ "0" + i }}
              </div>
              <h3 class="text-base font-bold md:mb-4 md:hidden">
                {{ item.title }}
              </h3>
            </div>
          </div>

          <div>
            <h3 class="mb-4 hidden text-lg font-bold md:block">
              {{ item.title }}
            </h3>
            <p class="text-darkGrayishBlue">
              {{ item.paragraph }}
            </p>
          </div>
        </li>
      </ul>
    </div>
  </section>
</template>
