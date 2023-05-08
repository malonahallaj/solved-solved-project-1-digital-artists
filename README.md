Download Link: https://assignmentchef.com/product/solved-solved-project-1-digital-artists
<br>
Project RequirementsRecreate your favorite childhood drawing on a Java applet. Your graphics artwork must satisfy the following requirements:  (5 pts) Overall canvas size is approximately 500×300  (5 pts) Draw a 500×300 rectangle in a color of your choice as the “background”  (20 pts) Include all of the following drawing elements:  Lines  Rectangle (or rounded rectangles)  Circles or ovals  Text (your name should be one of the text elements)  (10 pts) Use at least two colors. Refer to “Using Colors” section below.  (10 pts) Render the text using at least two different font sizes (or styles). Refer to “Changing Font” section below)  (10 pts) Use variables with meaningful names to hold different quantities related to the drawing (refer to “Using Variables” section below)  (15 pts) Use arithmetic expressions in method call arguments (refer to “Using Variables” section below)  (5 pts) The overall artwork should be attractive and well-balanced  (10 pts) Include a rough sketch of your artwork (use your phone, a digital camera, or a scanner to produce a digital image). Upload a digital copy to Bb Page 2/6  (10 pts) Well documented and elegant source code that follows Java Style Guide. Your paint() method shall include sufficient comments that explain what each block of code does Using Colors The setColor() method takes a single parameter of type Color and you have at least two options for using colors  Use one of the predefined Java colors: Color.RED, Color.BLUE, Color.WHITE … (The complete list of these colors can be found here). g.setColor (Color.MAGENTA);  Enter your own RGB values. The following example creates a color of RGB (54, 106, 184): Color myFavoriteBlue = new Color (54, 106, 184); g.setColor (myFavoriteBlue); A Google search for “color generator” should find online interactive tools that allow you to use a color palette. Using Variables Professional code uses variables to store values. Variables are typically declared at the top of a method and then assigned values as needed. Compare the following two techniques for drawing two black wheels. Obviously, the code on the right is easier to understand (and easier to modify). Also observe how arithmetic expression (wheelY + wheelDistance) is used as an argument to the method invocation. With no variables Using variables g.setColor (Color.BLACK); /* draw the front wheel */ g.fillOval (30, 40, 60, 60); /* draw the rear wheel */ g.fillOval (30, 130, 60, 60); int wheelX = 30; int wheelY = 40; int wheelDistance = 90; int wheelDia = 60; g.setColor (Color.BLACK); /* draw the front wheel */ g.fillOval (wheelX, wheelY, wheelDia, wheelDia); /* draw the rear wheel */ g.fillOval (wheelX, wheelY + wheelDistance, wheelDia, wheelDia);