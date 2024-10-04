---
layout: default
title: Anthropology
---

<div class="container">
    <h1>Anthropology</h1>

    <div class="table-layout">
        <div class="table-row">
            <div class="table-cell">
                <h2>Ethnography</h2>
                <p>
                    Ethnography involves the systematic study of people and cultures from the anthropological perspective. It allows researchers to gain a deep understanding of the social dynamics, traditions, and daily lives of various communities. I am particularly interested in exploring how cultural practices shape identity and foster connections within communities.
                </p>
            </div>
            <div class="table-cell">
                <h2>Download Ethnography Files</h2>
                <p>
                    You can download my ethnography files here:
                </p>
                <ul>
                    <li><a href="/assets/ethnography1.pdf" target="_blank" class="download-link">Ethnography File 1</a></li>
                    <li><a href="/assets/ethnography2.pdf" target="_blank" class="download-link">Ethnography File 2</a></li>
                </ul>
            </div>
        </div>

        <div class="table-row">
            <div class="table-cell">
                <h2>Harvard Summer School Experience</h2>
                <p>
                    At Harvard Summer School, I participated in a course on the Anthropology of Food and Foodways. This experience broadened my understanding of how culture influences food practices and communal relationships. I explored various culinary traditions and how they reflect social, economic, and cultural factors.
                </p>
            </div>
            <div class="table-cell">
                <h2>Download Harvard Course Files</h2>
                <p>
                    You can download my Harvard course files here:
                </p>
                <ul>
                    <li><a href="/assets/harvard1.pdf" target="_blank" class="download-link">Harvard File 1</a></li>
                    <li><a href="/assets/harvard2.pdf" target="_blank" class="download-link">Harvard File 2</a></li>
                </ul>
            </div>
        </div>

        <div class="table-row">
            <div class="table-cell">
                <h2>ManaBadi Experience</h2>
                <p>
                    ManaBadi is a Telugu school that focuses on teaching the Telugu language and cultural heritage. My time there was invaluable in reconnecting with my roots and understanding the significance of language in shaping cultural identity. I gained a deeper appreciation for my heritage and the importance of preserving cultural practices.
                </p>
            </div>
            <div class="table-cell">
                <h2>Upload Your ManaBadi Work</h2>
                <form action="/upload" method="post" enctype="multipart/form-data">
                    <input type="file" name="file" accept=".pdf" class="file-input">
                    <input type="submit" value="Upload PDF" class="submit-button">
                </form>
            </div>
        </div>
    </div>
</div>













.container {
    max-width: 1200px; /* Increased width for better layout */
    margin: auto;
    padding: 20px;
    background-color: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

h1 {
    text-align: center;
    color: #333;
    margin-bottom: 1rem;
}

h2 {
    color: #4a4a4a;
    font-size: 1.5rem;
    margin: 1.5rem 0 0.5rem;
}

.table-layout {
    display: table; /* Use table display for layout */
    width: 100%;
    margin-bottom: 2rem;
}

.table-row {
    display: table-row; /* Rows for the table */
}

.table-cell {
    display: table-cell; /* Cells for the table */
    padding: 20px;
    background-color: #ffffff; /* White background for sections */
    border-radius: 8px;
    box-shadow: 0 1px 5px rgba(0, 0, 0, 0.1);
    vertical-align: top; /* Align content to the top */
}

.file-input {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    margin-right: 10px;
}

.submit-button {
    padding: 10px 15px;
    background-color: #007bff; /* Button color */
    color: #ffffff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

.submit-button:hover {
    background-color: #0056b3; /* Button hover color */
}

.download-link {
    display: inline-block;
    padding: 10px 15px;
    background-color: #28a745; /* Download link color */
    color: #ffffff;
    border-radius: 4px;
    text-decoration: none;
    margin-top: 10px;
}

.download-link:hover {
    background-color: #218838; /* Download link hover color */
}
