<template>
  <div class="min-h-screen bg-gray-100">
    <main class="py-16">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div class="bg-white overflow-hidden shadow-sm sm:rounded-lg">
          <div class="p-6 text-gray-900">
            <h1 class="text-4xl font-bold text-center mb-8">Welcome to My Portfolio</h1>
            <p class="text-lg text-center text-gray-600 mb-12">This site is built with Laravel, Vue.js, Inertia.js, and TailwindCSS</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
              <Card
                title="Project 1"
                description="A sample project showcasing my skills in web development."
              >
                <button class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded">
                  Learn More
                </button>
              </Card>
              
              <Card
                title="Project 2"
                description="Another exciting project demonstrating my expertise."
              >
                <button class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded">
                  View Details
                </button>
              </Card>
              
              <Card
                title="Project 3"
                description="A collaborative project highlighting teamwork and innovation."
              >
                <button class="bg-purple-500 hover:bg-purple-600 text-white px-4 py-2 rounded">
                  Explore
                </button>
              </Card>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script setup>
import Card from '@/Components/Card.vue';
</script>