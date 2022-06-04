<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1> <b>Layout Design Process</b> </h1>
    <ol>
        <li>First crop the layout image</li>
        <li>Open inkscape and select the layout image</li>
        <li>save the image in svg format</li>
        <li>create a folder with project name and keep all the files ( cropped image, main layout images, raw template.html in it)</li>
        <li>Open the main project folder in VS-Code </li>
        <li>Copy the raw template code  and paste it in new project file.html </li>
        <li>Copy the raw image code from saved svg image file code(open svg image file in VS_CODE there we can find image raw code) and paste it in new project file.html in between ' < g >< /g >'tags </li>
        <li>remove the lines below '< g  >' and copy the image width and height in svg img. (file--> document properties. there we can find img width & height)</li>
        <li>By using GENERATORS folder--> index.html --> open it in browser , there we can get code for required no of plots .</li>
        <li>Copy that  plot numbers code and paste it in main project file after image raw code -->"" < /g >"" </li>
        <li>Then by using beizer marking option mark each every plot and save it </li>
        <li>Every time we save the plot box we get a code in svg code file </li>
        <li>copy that(d="--------") and paste in main project.html (d="---") </li>

    </ol>
</body>
</html>
