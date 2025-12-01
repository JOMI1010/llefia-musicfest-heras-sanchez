<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Llefià Music Fest - Contacto</title>
    <style>
        /* Capçalera */
        header {
            text-align: center;
            padding: 2rem 1rem;
            background-color: #1a1a1a;
        }

        nav {
            background-color: #222;
            padding: 0.5rem 1rem;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff8800;
        }

        /* Secció principal */
        main {
            max-width: 600px;
            margin: 2rem auto;
            padding: 1rem;
        }
        .section-title {
            color: #ff8800;
            font-size: 1.8rem;
            margin-bottom: 0.5rem;
        }
        .section-text {
            margin-bottom: 2rem;
            font-size: 1rem;
        }

        /* Formulari */
        form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        label {
            margin-bottom: 0.3rem;
        }
        input[type="text"],
        input[type="email"],
        select,
        textarea {
            padding: 0.6rem;
            border: 1px solid #333;
            border-radius: 8px;
            background-color: #1a1a1a;
            color: #fff;
            width: 100%;
        }
        textarea {
            resize: vertical;
        }
        .radio-group,
        .checkbox-group {
            display: flex;
            flex-direction: column;
            gap: 0.3rem;
        }

        /* Botó */
        button {
            padding: 0.8rem;
            background-color: #ff8800;
            color: #fff;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #e67600;
        }

        /* Peu de pàgina */
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #1a1a1a;
            margin-top: 2rem;
            font-size: 0.9rem;
            color: #aaa;
        }

