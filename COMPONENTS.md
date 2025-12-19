# 🦩 Reusable Components Library

## Button Component

```html
<!-- Primary Button -->
<a href="#" class="btn bg-red-600 text-white px-8 py-3 rounded-lg font-bold hover:bg-red-700 transition shadow-lg">
    📞 عنوان
</a>

<!-- Secondary Button -->
<a href="#" class="btn border-2 border-red-600 text-red-600 px-8 py-3 rounded-lg font-bold hover:bg-red-50 transition">
    🤖 عنوان
</a>
```

## Card Component

```html
<div class="bg-white dark:bg-slate-700 p-8 rounded-xl shadow hover:shadow-lg transition animate-scale-in" style="animation-delay: 0s">
    <div class="text-4xl mb-4">🏗️</div>
    <h4 class="text-xl font-bold mb-3 text-gray-900 dark:text-white">عنوان</h4>
    <p class="text-gray-600 dark:text-gray-400">فروتر</p>
</div>
```

## Product Card

```html
<div class="bg-white dark:bg-slate-700 rounded-xl overflow-hidden shadow hover:shadow-xl transition animate-fade-in-up" style="animation-delay: 0s">
    <img src="https://images.unsplash.com/photo-..." alt="محصول" class="w-full h-48 object-cover">
    <div class="p-6">
        <h4 class="text-xl font-bold mb-2 text-gray-900 dark:text-white">نام</h4>
        <p class="text-gray-600 dark:text-gray-400 mb-4">متن</p>
        <p class="text-red-600 font-bold text-lg">قیمت: مبلغ</p>
    </div>
</div>
```

## Feature Box

```html
<div class="flex gap-4 animate-slide-in-right" style="animation-delay: 0s">
    <div class="text-3xl flex-shrink-0">📍</div>
    <div>
        <h4 class="text-xl font-bold mb-2 text-gray-900 dark:text-white">عنوان</h4>
        <p class="text-gray-600 dark:text-gray-400">فروتر</p>
    </div>
</div>
```

## Contact Box

```html
<div class="flex gap-4">
    <span class="text-3xl">📞</span>
    <div>
        <h4 class="font-bold mb-1">عنوان</h4>
        <p class="text-gray-300">متن</p>
    </div>
</div>
```

## Table Row

```html
<tr>
    <td class="font-bold">محصول</td>
    <td>سایز</td>
    <td>واحد</td>
    <td>قیمت</td>
    <td><a href="https://wa.me/989113286812" class="text-red-600 font-bold hover:underline">پیام</a></td>
</tr>
```

## Section Container

```html
<section class="py-16 bg-gray-50 dark:bg-slate-800">
    <div class="max-w-6xl mx-auto px-4">
        <h3 class="text-3xl font-bold text-center mb-12 text-gray-900 dark:text-white">عنوان بخش</h3>
        <!-- Content here -->
    </div>
</section>
```

## Hero Section

```html
<section class="relative bg-gradient-to-br from-red-600 to-red-800 text-white py-20 overflow-hidden">
    <div class="absolute inset-0 opacity-10">
        <div class="absolute top-10 right-20 w-40 h-40 bg-white rounded-full blur-3xl"></div>
        <div class="absolute bottom-10 left-20 w-40 h-40 bg-red-400 rounded-full blur-3xl"></div>
    </div>
    
    <div class="max-w-6xl mx-auto px-4 relative z-10">
        <!-- Content here -->
    </div>
</section>
```

## Theme Toggle Button

```html
<button @click="darkMode = !darkMode" class="p-2 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800 transition" title="تغییر تم">
    <span x-show="!darkMode" class="text-xl">🌙</span>
    <span x-show="darkMode" class="text-xl">☀️</span>
</button>
```

## Animation Delays

```html
<!-- Use these delays for staggered animations -->
style="animation-delay: 0s"
style="animation-delay: 0.1s"
style="animation-delay: 0.2s"
style="animation-delay: 0.3s"
style="animation-delay: 0.4s"
```

## Useful Classes

- `bg-white dark:bg-slate-700` - Background
- `text-gray-900 dark:text-white` - Text color
- `border-gray-200 dark:border-gray-700` - Borders
- `hover:shadow-lg transition` - Hover effects
- `rounded-xl` - Border radius (12px)
- `max-w-6xl mx-auto px-4` - Container
- `py-16` - Vertical padding
- `gap-8` - Grid gap

---

## Color Palette

```
Red (Primary):
- #dc2626 (Main)
- #991b1b (Dark)
- #fecaca (Light)

Background:
- #ffffff (Light)
- #111827 (Dark)

Text:
- #1f2937 (Light Mode)
- #f3f4f6 (Dark Mode)

Gray:
- #e5e7eb (Light border)
- #374151 (Dark border)
```
