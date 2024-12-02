<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SoC Project GitPage</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <h1>SoC Project GitPage</h1>
        <nav>
            <ul>
                <li><a href="#code">Coding</a></li>
                <li><a href="#demo">Demo</a></li>
                <li><a href="#dev">Development</a></li>
            </ul>
        </nav>
    </header>

    <section id="code">
        <h2>Coding</h2>
        <p>The basis of he code for this project was gathered from my previous labs in SoCD.</p> 
        <img src="fpga-vga-verilog-main/docs/assets/images/cyc code.png" alt="Code depicting an if statement" width="500">
        <p>After that, I had to research how to make the switches work with te existing code. After my research, I found that I had to add to my constraints to make them compatible. </p>
        <img src="fpga-vga-verilog-main/docs/assets/images/constrCode.png" alt="Code showing the constraints of the switches" width="500">
        <p>The if else statements hold code for different flags and subsiquently be displayed when their respective switch is flipped, which will be shown in the demo section. </p>
    </section>

    <section id="demo">
        <h2>Demonstration</h2>
        <p>To demonstrate that the program is working as intended I have to show that the screen is displaying the flags in their intended order. The first switch is the Irish flag, the second is the Offaly flag, and the third is the Kenyan flag.</p>
        <div class="dem">
            <img src="fpga-vga-verilog-main/docs/assets/images/20241202_151759.jpg" alt="A picture of the switch turned on with the Irish flag on the screen" width="200">
            <img src="fpga-vga-verilog-main/docs/assets/images/20241202_151809.jpg" alt="A picture of the switch turned on with the Offaly flag on the screen" width="200">
            <img src="fpga-vga-verilog-main/docs/assets/images/20241202_151817.jpg" alt="A picture of the switch turned on with the Kenyan flag on the screen" width="200">
        </div>
        <p>Another way of demonstrating that the switches worked is to show the simulation working as intended through the testbench.</p>
        <div class="dem">
            <img src="fpga-vga-verilog-main/docs/assets/images/simCode.png" alt="A picture of the code for the testbench" width="350">
            <img src="fpga-vga-verilog-main/docs/assets/images/simDemo.png" alt="A picture of the simulation on the testbench" width="350">
        </div>
    </section>

    <section id="dev">
        <h2>Development</h2>
        <p>During the course of this project, there were developments in understanding and manipulating the code. While learning about the code and creating the project there were errors that will be detailed here.</p>
    </section>

    <footer>
        <p>Copyright © 2024 Mark</p>
    </footer>
</body>
