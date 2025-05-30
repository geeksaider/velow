<template>
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 md:py-24">
    <h1 class="text-3xl font-light text-gray-900 mb-16 text-center">О нас</h1>
    
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-20">
      <div>
        <img src="https://images.unsplash.com/photo-1586023492125-27b2c045efd7?ixlib=rb-1.2.1&auto=format&fit=crop&w=1200&q=80" 
             alt="Наш шоурум" 
             class="w-full h-auto rounded-md object-cover" 
             style="aspect-ratio: 4/3;">
      </div>
      <div class="flex flex-col justify-center">
        <h2 class="text-2xl font-light text-gray-900 mb-6">Наша история</h2>
        <p class="text-gray-600 mb-4">
          Velo — это бренд минималистичного декора для современного дома. Мы верим, что красота заключается в простоте, 
          а каждый предмет в вашем доме должен не только радовать глаз, но и быть функциональным.
        </p>
        <p class="text-gray-600 mb-4">
          Наша миссия — помочь создать гармоничное пространство, в котором приятно находиться. 
          Мы тщательно отбираем каждый предмет в нашей коллекции, обращая внимание на качество 
          материалов, экологичность и эстетику.
        </p>
        <p class="text-gray-600">
          Velo был основан в 2021 году командой дизайнеров и любителей минимализма, которые хотели 
          предложить рынку что-то особенное — аутентичные предметы декора с душой и характером.
        </p>
      </div>
    </div>
    
    <div class="mb-20">
      <h2 class="text-2xl font-light text-gray-900 mb-8 text-center">Наши ценности</h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="p-6 bg-white border border-gray-200 rounded-md">
          <div class="flex justify-center mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-gray-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9" />
            </svg>
          </div>
          <h3 class="text-xl font-medium text-gray-900 mb-2 text-center">Экологичность</h3>
          <p class="text-center text-gray-600">
            Мы стремимся к тому, чтобы наше производство оказывало минимальное влияние на окружающую среду. 
            Используем натуральные материалы и экологичную упаковку.
          </p>
        </div>
        
        <div class="p-6 bg-white border border-gray-200 rounded-md">
          <div class="flex justify-center mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-gray-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M7 12l3-3 3 3 4-4M8 21l4-4 4 4M3 4h18M4 4h16v12a1 1 0 01-1 1H5a1 1 0 01-1-1V4z" />
            </svg>
          </div>
          <h3 class="text-xl font-medium text-gray-900 mb-2 text-center">Качество</h3>
          <p class="text-center text-gray-600">
            Мы не идем на компромиссы в вопросах качества. Каждый предмет проходит тщательный контроль 
            перед тем, как попасть к вам в дом.
          </p>
        </div>
        
        <div class="p-6 bg-white border border-gray-200 rounded-md">
          <div class="flex justify-center mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-gray-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M12 11c0 3.517-1.009 6.799-2.753 9.571m-3.44-2.04l.054-.09A13.916 13.916 0 008 11a4 4 0 118 0c0 1.017-.07 2.019-.203 3m-2.118 6.844A21.88 21.88 0 0015.171 17m3.839 1.132c.645-2.266.99-4.659.99-7.132A8 8 0 008 4.07M3 15.364c.64-1.319 1-2.8 1-4.364 0-1.457.39-2.823 1.07-4" />
            </svg>
          </div>
          <h3 class="text-xl font-medium text-gray-900 mb-2 text-center">Уникальность</h3>
          <p class="text-center text-gray-600">
            Мы сотрудничаем с локальными дизайнерами и ремесленниками, чтобы предложить вам 
            уникальные предметы с характером и историей.
          </p>
        </div>
      </div>
    </div>
    
    <div class="mb-20">
      <h2 class="text-2xl font-light text-gray-900 mb-8 text-center">Наша команда</h2>
      
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
        <div>
          <div class="rounded-md overflow-hidden mb-4 bg-gray-100" style="aspect-ratio: 1/1;">
            <img src="https://images.unsplash.com/photo-1548142813-c348350df52b?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" 
                 alt="Елена Соколова" 
                 class="w-full h-full object-cover">
          </div>
          <h3 class="text-lg font-medium text-gray-900 mb-1 text-center">Елена Соколова</h3>
          <p class="text-gray-500 text-center">Основатель и CEO</p>
        </div>
        
        <div>
          <div class="rounded-md overflow-hidden mb-4 bg-gray-100" style="aspect-ratio: 1/1;">
            <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" 
                 alt="Алексей Петров" 
                 class="w-full h-full object-cover">
          </div>
          <h3 class="text-lg font-medium text-gray-900 mb-1 text-center">Алексей Петров</h3>
          <p class="text-gray-500 text-center">Креативный директор</p>
        </div>
        
        <div>
          <div class="rounded-md overflow-hidden mb-4 bg-gray-100" style="aspect-ratio: 1/1;">
            <img src="https://images.unsplash.com/photo-1573497019940-1c28c88b4f3e?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" 
                 alt="Мария Иванова" 
                 class="w-full h-full object-cover">
          </div>
          <h3 class="text-lg font-medium text-gray-900 mb-1 text-center">Мария Иванова</h3>
          <p class="text-gray-500 text-center">Менеджер по продукту</p>
        </div>
        
        <div>
          <div class="rounded-md overflow-hidden mb-4 bg-gray-100" style="aspect-ratio: 1/1;">
            <img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" 
                 alt="Дмитрий Кузнецов" 
                 class="w-full h-full object-cover">
          </div>
          <h3 class="text-lg font-medium text-gray-900 mb-1 text-center">Дмитрий Кузнецов</h3>
          <p class="text-gray-500 text-center">Дизайнер интерьеров</p>
        </div>
      </div>
    </div>
    
    <div>
      <h2 class="text-2xl font-light text-gray-900 mb-8 text-center">Наш шоурум</h2>
      
      <div class="bg-white border border-gray-200 rounded-md overflow-hidden">
        <div class="grid grid-cols-1 md:grid-cols-2">
          <div>
            <img src="https://images.unsplash.com/photo-1594026112284-02bb6f3352fe?ixlib=rb-1.2.1&auto=format&fit=crop&w=1200&q=80" 
                 alt="Наш шоурум" 
                 class="w-full h-full object-cover">
          </div>
          <div class="p-8 flex flex-col justify-center">
            <h3 class="text-xl font-medium text-gray-900 mb-4">Приходите к нам в гости</h3>
            <p class="text-gray-600 mb-6">
              Мы будем рады видеть вас в нашем шоуруме, где вы сможете увидеть всё многообразие 
              наших коллекций и получить консультацию по оформлению вашего интерьера.
            </p>
            <div>
              <p class="text-gray-900 font-medium mb-1">Адрес:</p>
              <p class="text-gray-600 mb-4">г. Москва, ул. Дизайнерская, д. 42</p>
              
              <p class="text-gray-900 font-medium mb-1">Время работы:</p>
              <p class="text-gray-600 mb-4">Пн-Пт: 10:00-20:00<br>Сб-Вс: 11:00-18:00</p>
              
              <p class="text-gray-900 font-medium mb-1">Телефон:</p>
              <p class="text-gray-600">+7 (999) 123-45-67</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutView'
}
</script>

<style scoped>
/* Оставляем пустым, так как используем utility-классы Tailwind */
</style>
