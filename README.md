# ds.02

## Visualización de Datos

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad Física 2024</title>
    <script type="text/javascript" src="https://public.tableau.com/javascripts/api/tableau-2.min.js"></script>
</head>
<body>
    <h1 style="text-align: center;">Actividad Física 2024</h1>
    <div id="vizContainer" style="width: 100%; height: 800px;"></div>

    <script type="text/javascript">
        // Tableau Public URL
        var tableauUrl = "https://public.tableau.com/views/Tableau-ActividadFsica/ActividadFisica2024";
        
        // Tableau options
        var options = {
            width: "100%",
            height: "800px",
            hideTabs: true,
            hideToolbar: true
        };

        // Embed Tableau dashboard
        var containerDiv = document.getElementById("vizContainer");
        var viz = new tableau.Viz(containerDiv, tableauUrl, options);
    </script>
</body>
</html>

