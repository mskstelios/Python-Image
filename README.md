<body>
<h1>Image Editor Application</h1>

<h2>Overview</h2>
<p>This project is a simple image editor built using Python. It provides a graphical user interface (GUI) for basic image manipulation tasks such as rotation, mirroring, applying filters (black & white, sharpness, blur), and saving the edited images. The application is built using the <code>PyQt5</code> library for the GUI and the <code>Pillow</code> library for image processing.</p>

<h2>Features</h2>
<ul>
    <li><strong>Open Images</strong>: Load images from a directory and display them in the application.</li>
    <li><strong>Rotate Left</strong>: Rotate images 90 degrees to the left.</li>
    <li><strong>Mirror</strong>: Flip images horizontally.</li>
    <li><strong>Black & White</strong>: Convert images to grayscale.</li>
    <li><strong>Sharpness</strong>: Enhance the sharpness of images.</li>
    <li><strong>Blur</strong>: Apply a blur effect to images.</li>
    <li><strong>Normal</strong>: Revert to the original, unmodified image.</li>
    <li><strong>Save Edited Image</strong>: Save the edited image to a specified directory.</li>
</ul>

<h2>Prerequisites</h2>
<p>Before you begin, ensure you have met the following requirements:</p>
<ul>
    <li><strong>Python 3.x</strong>: This application requires Python 3.x. You can download it from <a href="https://www.python.org/" target="_blank">python.org</a>.</li>
    <li><strong>PyQt5</strong>: Install PyQt5 for the GUI by running the command:</li>
</ul>
<pre><code>pip install PyQt5</code></pre>
<ul>
    <li><strong>Pillow</strong>: Install Pillow for image processing by running the command:</li>
</ul>
<pre><code>pip install Pillow</code></pre>

<h2>Installation</h2>
<ol>
    <li><strong>Clone the Repository</strong>:
        <pre><code>git clone https://github.com/mskstelios/Python-Image.git</code></pre>
    </li>
    <li><strong>Navigate to the Project Directory</strong>:
        <pre><code>cd Python-Image</code></pre>
    </li>
</ol>

<h2>Usage</h2>
<ol>
    <li><strong>Run the Application</strong>:
        <pre><code>python image.py</code></pre>
    </li>
    <li><strong>Using the Application</strong>:
        <ul>
            <li>Click on <strong>Open Folder</strong> to browse and select the directory containing your images.</li>
            <li>Choose an image from the list of files displayed on the left side.</li>
            <li>Apply any of the available filters using the checkboxes:
                <ul>
                    <li><strong>Left</strong>: Rotate the image 90 degrees to the left.</li>
                    <li><strong>Mirror</strong>: Flip the image horizontally.</li>
                    <li><strong>Sharpness</strong>: Enhance the sharpness of the image.</li>
                    <li><strong>B&amp;W</strong>: Convert the image to black and white.</li>
                    <li><strong>Blur</strong>: Apply a blur effect to the image.</li>
                    <li><strong>Normal</strong>: Revert to the original version of the image.</li>
                </ul>
            </li>
            <li>Click on <strong>Save Edited Image</strong> to save the modified image in a subfolder named <code>Modified</code> within the original image directory.</li>
        </ul>
    </li>
</ol>


