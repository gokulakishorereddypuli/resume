<!DOCTYPE html>
<html>

<head>
    <title>PDF in HTML</title>
</head>
<style>
    .pdf {
        width: 100%;
        aspect-ratio: 4 / 3;
    }

    .pdf,
    html,
    body {
        height: 100%;
        margin: 0;
        padding: 0;
    }

    h1,
    h3 {
        text-align: center;
    }

    h1 {
        color: green;
    }
</style>

<body>

    <h1>GeeksforGeeks</h1>
    <h3>Embedding the PDF file Using Object Tag</h3>
    <object class="pdf" 
            data=
"https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210101201653/PDF.pdf"
            width="800"
            height="500">
    </object>
</body>

</html>
