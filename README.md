# qb-core Drawtext Prodigy 2.0 Inspired

i know the export looks weard but hee! it works tips and tricks are welcome 

## Showcase 
![image](https://github.com/user-attachments/assets/680f8a34-da45-4912-81db-b6151e44053c)

## Dependencies

- [QBCore](https://github.com/qbcore-framework/qb-core)

# Usage

### Exports
	exports['qb-core']:DrawText('<span style="color: rgba(255, 255, 255, 0.5);"><span style="border: 1px solid rgba(255, 255, 255, 0.5); background-color: rgba(255, 255, 255, 0.2); border-radius: 5px; display: inline-block; width: 27px; height: 28px; text-align: center; line-height: 25px; position: relative; top: 1px; color: white;">E</span></span><span style="margin-left: 5px;"> OPEN DOOR</span>', 'left')

on the end you see the E and OPEN DOOR thats the text

### HTML part 

	<html>
  	<head>
    <link href="https://fonts.googleapis.com/css2?family=Alumni+Sans:ital@0;1&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/quasar@2.12.0/dist/quasar.prod.css" rel="stylesheet" type="text/css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
    <link href="https://fonts.googleapis.com/css2?family=Alumni+Sans:ital@0;1&display=swap" rel="stylesheet" type="text/css" />
    <link href="css/style.css" rel="stylesheet" />
    <script src="https://cdn.jsdelivr.net/npm/vue@3/dist/vue.global.prod.js" defer></script>
    <script src="https://cdn.jsdelivr.net/npm/quasar@2.12.0/dist/quasar.umd.prod.js" defer></script>
    <script type="module" src="js/app.js"></script>
    <script src="js/drawtext.js"></script>
    <link rel="stylesheet" href="css/drawtext.css">
 	 </head>
 	 <body style="font-family: 'Alumni Sans', sans-serif">
    <div id="q-app" style="min-height: 100vh"></div>
    <div id="drawtext-container">
      <div id="text" class="text"></div>
    </div>
  	</body>
	</html>

- Replace or take the lines from the fonts and font-family i dont know if the new QBcore version is made in a other way i have one older version before the big update 
