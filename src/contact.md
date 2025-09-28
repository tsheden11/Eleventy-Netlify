---
layout: base
title: Contact
---

<!-- Hero Section -->
<section class="py-16 bg-gradient-to-br from-blue-600 to-teal-500 text-white">
  <div class="container mx-auto px-6 text-center">
    <h1 class="text-4xl font-bold mb-4">Let's Plan Your Bhutan Journey</h1>
    <p class="text-xl text-blue-100 max-w-2xl mx-auto">
      Ready to experience authentic Bhutan? Our family is here to help you create memories that last a lifetime.
    </p>
  </div>
</section>

<!-- Contact Content -->
<section class="py-16 bg-white">
  <div class="container mx-auto px-6">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
      
      <!-- Contact Information -->
      <div class="space-y-8">
        <div>
          <h2 class="text-2xl font-bold text-gray-900 mb-6">Get in Touch</h2>
          <p class="text-gray-600 mb-8">
            Whether you're dreaming of cultural immersion, mountain adventures, or peaceful retreats, we're here to make it happen. Contact our family team today.
          </p>
        </div>

        <!-- Contact Cards -->
        <div class="space-y-6">
          <div class="bg-yellow-50 rounded-2xl p-6 border border-yellow-100">
            <div class="flex items-center mb-4">
              <div class="w-12 h-12 bg-yellow-500 rounded-full flex items-center justify-center">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                </svg>
              </div>
              <div class="ml-4">
                <h3 class="text-lg font-semibold text-gray-900">Email Us</h3>
                <p class="text-gray-700">info@kotatravels.bt</p>
                <p class="text-sm text-gray-500">We respond within 24 hours</p>
              </div>
            </div>
          </div>

          <div class="bg-orange-50 rounded-2xl p-6 border border-orange-100">
            <div class="flex items-center mb-4">
              <div class="w-12 h-12 bg-orange-500 rounded-full flex items-center justify-center">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                </svg>
              </div>
              <div class="ml-4">
                <h3 class="text-lg font-semibold text-gray-900">Call Us</h3>
                <p class="text-gray-700">+975 XXXX XXXX</p>
                <p class="text-sm text-gray-500">Available 9 AM - 6 PM (BTT)</p>
              </div>
            </div>
          </div>

          <div class="bg-teal-50 rounded-2xl p-6 border border-teal-100">
            <div class="flex items-center mb-4">
              <div class="w-12 h-12 bg-teal-500 rounded-full flex items-center justify-center">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                </svg>
              </div>
              <div class="ml-4">
                <h3 class="text-lg font-semibold text-gray-900">Visit Us</h3>
                <p class="text-gray-700">Thimphu, Bhutan</p>
                <p class="text-sm text-gray-500">By appointment only</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Contact Form -->
      <div class="bg-stone-50 rounded-2xl p-8">
        <h3 class="text-2xl font-bold text-gray-900 mb-6">Send us a Message</h3>
        <form name="contact" method="POST" data-netlify="true" class="space-y-6">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
              <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Full Name</label>
              <input type="text" id="name" name="name" required 
                     class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent transition-colors bg-white">
            </div>
            
            <div>
              <label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email Address</label>
              <input type="email" id="email" name="email" required 
                     class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent transition-colors bg-white">
            </div>
          </div>
          
          <div>
            <label for="subject" class="block text-sm font-medium text-gray-700 mb-2">What interests you?</label>
            <select id="subject" name="subject" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent transition-colors bg-white">
              <option value="">Select tour type</option>
              <option value="cultural">Cultural Tours</option>
              <option value="mountain-biking">Mountain Biking</option>
              <option value="relaxation">Relaxation & Wellness</option>
              <option value="custom">Custom Itinerary</option>
              <option value="other">Other Inquiry</option>
            </select>
          </div>
          
          <div>
            <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Tell us about your dream Bhutan experience</label>
            <textarea id="message" name="message" rows="5" required placeholder="Share your travel dates, group size, interests, and any special requests..."
                      class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent transition-colors bg-white"></textarea>
          </div>
          
          <button type="submit" class="w-full bg-gradient-to-r from-yellow-500 to-orange-500 hover:from-yellow-600 hover:to-orange-600 text-white font-semibold py-3 px-6 rounded-lg transition-all duration-200 transform hover:scale-105">
            Start Planning My Journey
          </button>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- Additional Info -->
<section class="py-12 bg-gradient-to-r from-orange-500 to-yellow-500 text-white">
  <div class="container mx-auto px-6 text-center">
    <h3 class="text-2xl font-bold mb-4">Why Choose Kota Travels?</h3>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-8">
      <div>
        <div class="text-3xl mb-2">🏡</div>
        <h4 class="font-semibold mb-2">Family-Run Business</h4>
        <p class="text-orange-100 text-sm">Personal attention and genuine care for every guest</p>
      </div>
      <div>
        <div class="text-3xl mb-2">🌍</div>
        <h4 class="font-semibold mb-2">Global Perspective</h4>
        <p class="text-orange-100 text-sm">We've lived abroad and understand international travelers</p>
      </div>
      <div>
        <div class="text-3xl mb-2">🌱</div>
        <h4 class="font-semibold mb-2">Sustainable Tourism</h4>
        <p class="text-orange-100 text-sm">Responsible travel that respects our culture and environment</p>
      </div>
    </div>
  </div>
</section>