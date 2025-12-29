<h1>Lazy Read</h1>

<p>A hands-free PDF reader that uses facial tracking for navigation, enabling users to turn pages through head movements alone.</p>

<h2>Overview</h2>

<p>Ever wanted to read manga while your hands are BUSY? LazyRead uses your face to turn pages handsfree.</p>

<p>The app uses your webcam to track where you're looking and turns pages when you glance towards the edges of your screen. No clicking, no scrolling</p>

<h2>Features</h2>

<ul>
<li><strong>Facial Tracking Navigation</strong>: Uses MediaPipe Face Mesh for precise facial landmark detection</li>
<li><strong>Intuitive Zone-Based Control</strong>: Navigate by looking towards screen edges - left to go back, right to go forward</li>
<li><strong>Visual Feedback System</strong>: Real-time cursor with progress ring showing dwell time</li>
<li><strong>Customisable Settings</strong>: Adjustable sensitivity, trigger zones, and dwell times</li>
<li><strong>PDF Rendering</strong>: Built-in PDF.js integration for smooth document display</li>
<li><strong>Responsive Design</strong>: Clean, dark-themed interface optimised for reading</li>
</ul>

<h2>How It Works</h2>

<ol>
<li><strong>Load a PDF</strong>: Upload any PDF document through the file picker</li>
<li><strong>Start Camera</strong>: Enable webcam access for facial tracking</li>
<li><strong>Navigate Naturally</strong>: Look towards the left or right edges of the screen</li>
<li><strong>Visual Confirmation</strong>: A green progress ring fills up during dwell time</li>
<li><strong>Automatic Page Turn</strong>: Pages change when the dwell timer completes</li>
</ol>

<h2>Technical Implementation</h2>

<ul>
<li><strong>Frontend</strong>: Pure HTML5, CSS3, and JavaScript</li>
<li><strong>Computer Vision</strong>: MediaPipe Face Mesh for facial landmark detection</li>
<li><strong>PDF Processing</strong>: PDF.js for document rendering</li>
<li><strong>Real-time Processing</strong>: Smooth cursor tracking with configurable smoothing algorithms</li>
</ul>

<h2>Configuration Options</h2>

<ul>
<li><strong>Sensitivity</strong>: Adjust how responsive the cursor is to head movements</li>
<li><strong>Trigger Zone</strong>: Set the screen edge percentage for navigation activation</li>
<li><strong>Dwell Time</strong>: Configure how long to look in a direction before page turns</li>
</ul>

<h2>Browser Compatibility</h2>

<p>Requires a modern web browser with:</p>
<ul>
<li>WebRTC support for camera access</li>
<li>WebGL for MediaPipe processing</li>
<li>ES6+ JavaScript features</li>
</ul>

<h2>Use Cases</h2>

<ul>
<li>Accessibility tool for users with limited hand mobility</li>
<li>Hands-free reading during cooking, exercising, or other activities</li>
<li>Presentation mode for documents</li>
<li>Educational tool for demonstrating computer vision applications</li>
</ul>

<h2>Getting Started</h2>

<p>Simply open the HTML file in a modern web browser, grant camera permissions, load a PDF, and start reading hands-free!</p>

<hr>

<p><em>Built with modern web technologies for seamless, accessible document navigation.</em></p>
