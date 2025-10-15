---
permalink: /
title: "Welcome to my personal website."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm **Mohsen**, a researcher and Ph.D. candidate in Mechanical Engineering at Washington State University. My academic journey focuses on developing control theories, implementing them on real robots, and exploring robot interactions with humans.  
Here, you'll find an overview of my professional and academic endeavors. This includes my ongoing research projects, publications, academic courses, and personal insights.

<img src="images/Hierarchical_Control_Structure.png" alt="Welcome Image" style="width:75%;">

## Latest News and Updates:

- **Upcoming Talks:** I will be presenting my paper in MECC'25, happening October 5-8, 2025, in Pittsburgh, Pennsylvania, USA.
- **Recent Publications:** My latest paper "Practical considerations for implementing robust-to-early termination model predictive control" has been published in Systems & Control Letters.
- **Community Engagement:** Stay tuned.

Thank you for visiting my site. Whether you're a fellow researcher, a prospective student, or simply curious about what I'm interested in, I hope you find the information here both informative and inspiring. Please feel free to reach out if you have any questions or wish to discuss potential collaborations.

-----------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohsen | Personal Website</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-white text-gray-800">

    <div class="container mx-auto max-w-5xl px-6 py-12">
        <!-- Header Navigation -->
        <header class="flex justify-end items-center mb-16">
            <nav class="space-x-8">
                <a href="#about" class="text-gray-600 hover:text-black font-medium">Home</a>
                <a href="#research" class="text-gray-600 hover:text-black font-medium">Research</a>
                <a href="#news" class="text-gray-600 hover:text-black font-medium">News</a>
                <!-- Add more links as needed -->
            </nav>
        </header>

        <main>
            <!-- About Me Section -->
            <section id="about" class="flex flex-col md:flex-row items-center gap-10 md:gap-12 mb-20">
                <!-- Profile Image -->
                <div class="flex-shrink-0">
                    <!-- Placeholder for your profile picture. Replace the src with the path to your image. -->
                    <img src="https://placehold.co/200x200/EFEFEF/333333?text=Mohsen" alt="Mohsen" class="rounded-full w-40 h-40 md:w-48 md:h-48 object-cover border-4 border-gray-100 shadow-md">
                </div>

                <!-- Bio -->
                <div class="text-center md:text-left">
                    <h1 class="text-4xl md:text-5xl font-bold mb-4">Mohsen</h1>
                    <p class="text-lg text-gray-700 leading-relaxed mb-4">
                        I'm a researcher and Ph.D. candidate in Mechanical Engineering at Washington State University. My academic journey focuses on developing control theories, implementing them on real robots, and exploring robot interactions with humans. Here, you'll find an overview of my professional and academic endeavors.
                    </p>
                    <div class="flex justify-center md:justify-start space-x-4 text-blue-600 font-medium">
                        <a href="#" class="hover:underline">CV</a>
                        <span>/</span>
                        <a href="#" class="hover:underline">LinkedIn</a>
                        <span>/</span>
                        <a href="#" class="hover:underline">Google Scholar</a>
                    </div>
                </div>
            </section>
            
            <!-- Research Image/Diagram Section -->
            <section id="research-image" class="mb-20">
                 <h2 class="text-3xl font-bold text-center mb-8">Research Overview</h2>
                 <div class="bg-gray-50 p-4 rounded-lg shadow-sm flex justify-center">
                    <!-- Placeholder for your research image. -->
                    <img src="https://placehold.co/800x450/FFFFFF/333333?text=Hierarchical+Control+Structure" alt="Hierarchical Control Structure Diagram" class="max-w-full h-auto rounded-md">
                 </div>
                 <p class="text-center text-gray-600 mt-3 text-sm">A diagram representing my research on hierarchical control structures.</p>
            </section>

            <!-- Latest News Section -->
            <section id="news">
                <h2 class="text-3xl font-bold text-center mb-12">Latest News and Updates</h2>
                <div class="space-y-6 max-w-3xl mx-auto">
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <h3 class="font-bold text-lg mb-1">Upcoming Talks</h3>
                        <p class="text-gray-700">I will be presenting my paper in MECC'25, happening October 5-8, 2025, in Pittsburgh, Pennsylvania, USA.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <h3 class="font-bold text-lg mb-1">Recent Publications</h3>
                        <p class="text-gray-700">My latest paper "Practical considerations for implementing robust-to-early termination model predictive control" has been published in Systems & Control Letters.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <h3 class="font-bold text-lg mb-1">Community Engagement</h3>
                        <p class="text-gray-700">Stay tuned for updates on my community engagement activities.</p>
                    </div>
                </div>
            </section>
        </main>

        <!-- Footer -->
        <footer class="text-center text-gray-500 mt-20 py-6 border-t">
            <p>&copy; 2024 Mohsen. All Rights Reserved.</p>
        </footer>
    </div>

</body>
</html>
