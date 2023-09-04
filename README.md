# Tailwind
Different ways to Use Tailwind

1) **Utility First** - In this task we remake a Danger Sign built with the help of CSS using Tailwind. Tailwind helps to get the things done with less amount of code and helps us to get the code user friendly. Tailwind Utility First" is a concept related to the Tailwind CSS framework, which is a popular utility-first CSS framework. Utility-first CSS frameworks, like Tailwind CSS, prioritize building web interfaces by composing utility classes rather than writing custom CSS from scratch.

In the context of Tailwind CSS, "Utility First" means that you start by applying pre-defined utility classes directly to your HTML elements to style and layout your website. These utility classes provide low-level styling, such as setting margins, padding, fonts, colors, and more. Instead of writing custom CSS, you use these classes to quickly style your elements.
Use of Tailwind:::::::----------------------------------------------:::::::::::::::::::
    <!-- Tailwind Version -->
    <div class="flex items-center p-6 max-w-sm mx-auto bg-white rounded-xl shadow-lg space-x-4 mt-12">
      <img class="w-12 h-12" src="../assets/img/warning.svg">
      <div>
        <div class="text-xl font-medium text-black">Are u Sure?</div>
        <p class="text-slate-500">You are about to delete a post</p>
      </div>
    </div>


    
2)** Colours** - Tailwind CSS is a popular utility-first CSS framework that provides a set of predefined colors as part of its default configuration. These colors are designed to be easily applied to elements in your web application without the need for custom CSS.

As of my last knowledge update in September 2021, here are some of the default colors available in Tailwind CSS:

Gray Colors:

gray-50 to gray-900: Shades of gray from lightest to darkest.
Red Colors:

red-50 to red-900: Shades of red from lightest to darkest.
Yellow Colors:

yellow-50 to yellow-900: Shades of yellow from lightest to darkest.
Green Colors:

green-50 to green-900: Shades of green from lightest to darkest.
Blue Colors:

blue-50 to blue-900: Shades of blue from lightest to darkest.
Indigo Colors:

indigo-50 to indigo-900: Shades of indigo from lightest to darkest.
Purple Colors:

purple-50 to purple-900: Shades of purple from lightest to darkest.
Pink Colors:

pink-50 to pink-900: Shades of pink from lightest to darkest.
White and Black Colors:

white and black: Solid white and black colors.
Transparent Color:

transparent: A transparent color that can be used for various purposes.
These color classes can be applied to text, backgrounds, borders, and other elements in your HTML markup. You can also use additional classes like text-{color}, bg-{color}, and border-{color} to style specific properties with these colors.


3) **Container Spacing**- In Tailwind CSS, you can control container spacing by using margin and padding utility classes. The container spacing refers to the spacing around and within containers, such as divs or sections, to control their margins and padding. You can adjust these spacing values according to your design requirements.

Here are some common classes to control container spacing in Tailwind CSS:

Margin Classes:

m-{size}: Adds margin to all sides of the container.

Example: m-4 adds a margin of 1rem (16px) to all sides.
mx-{size} and my-{size}: Adds horizontal and vertical margins, respectively.

Example: mx-2 adds horizontal margin, and my-6 adds vertical margin.
mt-{size}, mb-{size}, ml-{size}, mr-{size}: Adds margin to specific sides (top, bottom, left, right).

Example: mt-8 adds top margin of 2rem (32px).
Padding Classes:

p-{size}: Adds padding to all sides of the container.

Example: p-3 adds padding of 0.75rem (12px) to all sides.
px-{size} and py-{size}: Adds horizontal and vertical padding, respectively.

Example: px-4 adds horizontal padding, and py-6 adds vertical padding.
pt-{size}, pb-{size}, pl-{size}, pr-{size}: Adds padding to specific sides (top, bottom, left, right).

Example: pt-8 adds top padding of 2rem (32px).
You can replace {size} with numeric values or use predefined spacing sizes such as 1, 2, 3, etc., or use spacing sizes like sm, md, lg, xl, and 2xl to control the spacing. For example, m-4 would add a margin of 1rem, and mt-8 would add a top margin of 2rem.
<div class="container mx-auto p-4">
  <!-- Content goes here -->
</div>
