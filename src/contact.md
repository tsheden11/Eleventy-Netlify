---
layout: base.html
title: Contact
---

<div class="bg-white">
  <!-- Header -->
  <div class="text-center mb-12">
    <h1 class="text-4xl font-bold text-gray-900 mb-4">Get In Touch</h1>
    <p class="text-xl text-gray-600 max-w-2xl mx-auto">
      We'd love to hear from you. Send us a message and we'll respond as soon as possible.
    </p>
  </div>

  <!-- Contact Grid -->
  <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
    <!-- Contact Info -->
    <div class="space-y-8">
      <div class="bg-white rounded-lg shadow-md p-6 border border-gray-100">
        <div class="flex items-center mb-4">
          <div class="bg-blue-100 p-3 rounded-full">
            <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
            </svg>
          </div>
          <div class="ml-4">
            <h3 class="text-lg font-semibold text-gray-900">Email</h3>
            <p class="text-gray-600">your-email@example.com</p>
          </div>
        </div>
      </div>

      <div class="bg-white rounded-lg shadow-md p-6 border border-gray-100">
        <div class="flex items-center mb-4">
          <div class="bg-green-100 p-3 rounded-full">
            <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
            </svg>
          </div>
          <div class="ml-4">
            <h3 class="text-lg font-semibold text-gray-900">Phone</h3>
            <p class="text-gray-600">(555) 123-4567</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Contact Form -->
    <div class="bg-white rounded-lg shadow-md p-6 border border-gray-100">
      <form name="contact" method="POST" data-netlify="true" class="space-y-6">
        <div>
          <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Name</label>
          <input type="text" id="name" name="name" required 
                 class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-colors">
        </div>
        
        <div>
          <label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
          <input type="email" id="email" name="email" required 
                 class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-colors">
        </div>
        
        <div>
          <label for="subject" class="block text-sm font-medium text-gray-700 mb-2">Subject</label>
          <input type="text" id="subject" name="subject" 
                 class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-colors">
        </div>
        
        <div>
          <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
          <textarea id="message" name="message" rows="5" required 
                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-colors"></textarea>
        </div>
        
        <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-medium py-3 px-4 rounded-lg transition-colors duration-200">
          Send Message
        </button>
      </form>
    </div>
  </div>
</div>
