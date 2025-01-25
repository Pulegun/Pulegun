<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pulegun</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-sans">
    <!-- Header -->
    <header class="bg-gray-800 shadow-lg">
        <div class="container mx-auto px-4 py-6 flex justify-between items-center">
            <h1 class="text-3xl font-bold">Proyecto Musical y Audiovisual</h1>
            <nav class="space-x-4">
                <a href="#sobre" class="hover:underline">Sobre Nosotros</a>
                <a href="#galeria" class="hover:underline">Galería</a>
                <a href="#contacto" class="hover:underline">Contacto</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gray-700 py-20 text-center">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold mb-4">Somos Pulegun!</h2>
            <p class="text-lg mb-6">Sumérgete en un viaje creativo que combina sonidos únicos con imágenes impactantes.</p>
            <a href="#galeria" class="bg-indigo-600 hover:bg-indigo-500 text-white py-2 px-4 rounded-lg">Descubre Más</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="sobre" class="py-16">
        <div class="container mx-auto px-4">
            <h3 class="text-3xl font-bold mb-6">Sobre Nosotros</h3>
            <p class="text-lg leading-relaxed">
                Somos un colectivo creativo dedicado a la producción musical y audiovisual. Nuestro objetivo es conectar con las emociones a través del arte, creando experiencias que trasciendan.
            </p>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="galeria" class="py-16 bg-gray-800">
        <div class="container mx-auto px-4">
            <h3 class="text-3xl font-bold mb-6">Galería</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <div class="bg-gray-700 p-4 rounded-lg shadow-lg">
                    <img src="https://via.placeholder.com/300" alt="Imagen 1" class="rounded-lg mb-4">
                    <p>Descripción de la imagen o proyecto audiovisual.</p>
                </div>
                <div class="bg-gray-700 p-4 rounded-lg shadow-lg">
                    <img src="https://via.placeholder.com/300" alt="Imagen 2" class="rounded-lg mb-4">
                    <p>Descripción de la imagen o proyecto audiovisual.</p>
                </div>
                <div class="bg-gray-700 p-4 rounded-lg shadow-lg">
                    <img src="https://via.placeholder.com/300" alt="Imagen 3" class="rounded-lg mb-4">
                    <p>Descripción de la imagen o proyecto audiovisual.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-16">
        <div class="container mx-auto px-4">
            <h3 class="text-3xl font-bold mb-6">Contacto</h3>
            <form class="space-y-4">
                <div>
                    <label for="nombre" class="block text-sm font-medium">Nombre</label>
                    <input type="text" id="nombre" name="nombre" class="w-full bg-gray-800 text-white rounded-lg py-2 px-4">
                </div>
                <div>
                    <label for="email" class="block text-sm font-medium">Correo Electrónico</label>
                    <input type="email" id="email" name="email" class="w-full bg-gray-800 text-white rounded-lg py-2 px-4">
                </div>
                <div>
                    <label for="mensaje" class="block text-sm font-medium">Mensaje</label>
                    <textarea id="mensaje" name="mensaje" class="w-full bg-gray-800 text-white rounded-lg py-2 px-4"></textarea>
                </div>
                <button type="submit" class="bg-indigo-600 hover:bg-indigo-500 text-white py-2 px-4 rounded-lg">Enviar</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 py-6">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2025 Proyecto Musical y Audiovisual. Todos los derechos reservados.</p>
        </div>
    </footer>
</body>
</html>
