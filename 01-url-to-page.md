When you type a URL into your browser and press Enter, several steps happen before the page appears:

The browser checks the URL. It identifies the website’s address and the page you requested. It may also check its cache for a saved copy of the page or information it can reuse.

The browser finds the server’s address. A website name, such as example.com, is easy for people to remember, but computers use IP addresses. The browser asks the Domain Name System (DNS) to find the IP address for the website. If that information is already cached, this step may be quicker.

The browser connects to the server. Using the IP address, it establishes a connection with the web server. For a secure site using HTTPS, the browser and server also negotiate an encrypted connection and verify the site’s security certificate.

The browser requests the page. The browser sends an HTTP or HTTPS request that includes details such as the page it wants. The server receives the request and works out what to send back.

The server sends a response. The response usually includes HTML, which describes the page’s content and structure. It may also refer to other files, such as CSS for styling, JavaScript for interactive features, and images or fonts.

The browser downloads and processes the files. It reads the HTML and requests the additional resources needed for the page. CSS determines how elements should look, while JavaScript can add behavior or update content.

The browser displays the page. It combines the content, styles, images, and other resources, then draws the page on the screen. Some parts may appear before all resources finish loading, and scripts may continue updating the page afterward.

In short: the browser looks up the website’s address, connects to its server, requests the page, receives its files, and assembles them into the page you see.