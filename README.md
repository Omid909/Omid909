- 👋 Hi, I’m @Omid909
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Omid909/Omid909 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---><!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Immobilien Finanzierung</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Finden Sie die beste Finanzierung</h1>
            <p>Wählen Sie eine Option, um Ihre Finanzierungsanfrage zu starten:</p>
        </div>
    </header>

    <main>
        <section class="finance-options">
            <div class="option-card" data-option="Anschlussfinanzierung">
                <img src="anschlussfinanzierung.jpg" alt="Anschlussfinanzierung">
                <h2>Anschlussfinanzierung</h2>
            </div>

            <div class="option-card" data-option="Eigenes Bauvorhaben">
                <img src="bauvorhaben.jpg" alt="Eigenes Bauvorhaben">
                <h2>Eigenes Bauvorhaben</h2>
            </div>

            <div class="option-card" data-option="Privatkredit">
                <img src="privatkredit.jpg" alt="Privatkredit">
                <h2>Privatkredit</h2>
            </div>

            <div class="option-card" data-option="Immobilienkauf">
                <img src="immobilienkauf.jpg" alt="Immobilienkauf">
                <h2>Immobilienkauf</h2>
            </div>

            <div class="option-card" data-option="Modernisierung">
                <img src="modernisierung.jpg" alt="Modernisierung">
                <h2>Modernisierung</h2>
            </div>

            <div class="option-card" data-option="Kapitalbeschaffung">
                <img src="kapitalbeschaffung.jpg" alt="Kapitalbeschaffung">
                <h2>Kapitalbeschaffung</h2>
            </div>

            <div class="option-card" data-option="Umschuldung">
                <img src="Umschuldung.jpg" alt="Umschuldung">
                <h2>Schulung</h2>
            </div>

            <div class="option-card" data-option="Tiny Haus">
                <img src="tinyhaus.jpg" alt="Tiny Haus">
                <h2>Tiny Haus</h2>
            </div>
        </section>

        <div id="form-container" class="hidden">
            <h2 id="form-title"></h2>
            <form id="details-form">
                <div id="questions-container">
                    <!-- Fragen werden dynamisch eingefügt -->
                </div>
                <button type="submit">Absenden</button>
            </form>
        </div>
    </main>

    <footer>
        <p>© 2024 Immobilien Finanzierung</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
