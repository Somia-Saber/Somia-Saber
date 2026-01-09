<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Developer Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { background-color: #0f172a; color: white; scroll-behavior: smooth; }
        .hero-gradient { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); }
        .card:hover { transform: translateY(-10px); transition: 0.3s; border-color: #2dd4bf; }
    </style>
</head>
<body>

    <nav class="p-6 flex justify-between items-center max-w-6xl mx-auto">
        <h1 class="text-2xl font-bold text-teal-400 underline">Dev.Portfolio</h1>
        <div class="space-x-6">
            <a href="#projects" class="hover:text-teal-400">Projects</a>
            <a href="#skills" class="hover:text-teal-400">Skills</a>
            <a href="mailto:your-email@example.com" class="bg-teal-500 px-4 py-2 rounded shadow-lg hover:bg-teal-600 transition">Contact Me</a>
        </div>
    </nav>

    <section class="hero-gradient h-screen flex flex-col justify-center items-center text-center px-4">
        <h2 class="text-5xl md:text-7xl font-extrabold mb-4">Full-Stack <span class="text-teal-400">Developer</span></h2>
        <p class="text-gray-400 text-xl max-w-2xl">Building scalable web applications with Angular, ASP.NET Core, and modern technologies. Focused on clean code and efficient solutions.</p>
        <div class="mt-8">
            <a href="#projects" class="border border-teal-400 text-teal-400 px-8 py-3 rounded-full hover:bg-teal-400 hover:text-white transition">View My Work</a>
        </div>
    </section>

    <section id="projects" class="py-20 max-w-6xl mx-auto px-4">
        <h3 class="text-3xl font-bold mb-12 border-b border-teal-400 inline-block">Featured Projects</h3>
        <div class="grid md:grid-cols-2 gap-8">
            <div class="card p-6 rounded-xl border border-gray-700 bg-slate-800">
                <h4 class="text-xl font-bold mb-2">Time Schedule Management System</h4>
                <p class="text-gray-400 mb-4">A robust management system for Ain Shams University using modern web frameworks to handle complex scheduling.</p>
                <div class="flex gap-2">
                    <span class="text-xs bg-teal-900 text-teal-300 px-2 py-1 rounded">Angular</span>
                    <span class="text-xs bg-blue-900 text-blue-300 px-2 py-1 rounded">ASP.NET Core</span>
                </div>
            </div>
            <div class="card p-6 rounded-xl border border-gray-700 bg-slate-800">
                <h4 class="text-xl font-bold mb-2">Dental X-Ray AI Analysis</h4>
                <p class="text-gray-400 mb-4">Graduation project (Grade A+) integrating Deep Learning models into a functional web interface for medical analysis.</p>
                <div class="flex gap-2">
                    <span class="text-xs bg-yellow-900 text-yellow-300 px-2 py-1 rounded">Python</span>
                    <span class="text-xs bg-purple-900 text-purple-300 px-2 py-1 rounded">Deep Learning</span>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="py-20 bg-slate-900">
        <div class="max-w-6xl mx-auto px-4 text-center">
            <h3 class="text-3xl font-bold mb-12">Technical Stack</h3>
            <div class="flex flex-wrap justify-center gap-10">
                <div class="flex flex-col items-center"><i class="fab fa-angular text-5xl text-red-500"></i><span class="mt-2">Angular</span></div>
                <div class="flex flex-col items-center"><i class="fas fa-code text-5xl text-blue-500"></i><span class="mt-2">ASP.NET Core</span></div>
                <div class="flex flex-col items-center"><i class="fas fa-database text-5xl text-orange-500"></i><span class="mt-2">SQL / MySQL</span></div>
                <div class="flex flex-col items-center"><i class="fab fa-php text-5xl text-indigo-400"></i><span class="mt-2">PHP</span></div>
            </div>
        </div>
    </section>

    <footer class="p-10 text-center text-gray-500 border-t border-gray-800">
        <p>© 2026 Developer Portfolio | Built with Passion</p>
    </footer>

</body>
</html>
