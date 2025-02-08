<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ant Colony Optimization Simulator - README</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; }
        .container { max-width: 800px; margin: auto; padding: 20px; }
        details { margin-bottom: 10px; }
        summary { font-size: 1.2em; font-weight: bold; cursor: pointer; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Ant Colony Optimization Simulator</h1>
        <p><em>Solving complex optimization problems using the power of swarm intelligence.</em></p>
        <h2>Table of Contents</h2>
        <ul>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#technologies">Technologies Used</a></li>
            <li><a href="#working">Working</a></li>
            <li><a href="#algorithms">Algorithms Used</a></li>
        </ul>
        <details>
            <summary id="introduction">📌 Introduction</summary>
            <p>The <strong>Ant Colony Optimization Simulator</strong> is a web-based tool that simulates the behavior of ants to solve optimization problems such as the <strong>Traveling Salesman Problem (TSP)</strong>. It visualizes how artificial ants traverse paths, deposit pheromones, and iteratively improve solutions to find the shortest route between multiple nodes.</p>
        </details>
        <details>
            <summary id="technologies">🛠️ Technologies Used</summary>
            <ul>
                <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
                <li><strong>Visualization:</strong> Fabric.js for rendering nodes and paths</li>
                <li><strong>Data Handling:</strong> CSV parsing for node coordinates</li>
                <li><strong>Graph Plotting:</strong> Chart.js for real-time distance tracking</li>
                <li><strong>Utilities:</strong> Various JavaScript helper functions for algorithm implementation</li>
            </ul>
        </details>
        <details>
            <summary id="working">⚙️ Working</summary>
            <ol>
                <li><strong>User Input:</strong> Nodes (locations) are added manually or loaded via CSV files.</li>
                <li><strong>Simulation Start:</strong> Ants move between nodes based on pheromone trails and heuristic information.</li>
                <li><strong>Pheromone Update:</strong> After each iteration, pheromones evaporate and get reinforced on shorter paths.</li>
                <li><strong>Path Optimization:</strong> The algorithm refines the path selection over multiple generations.</li>
                <li><strong>Visualization:</strong> Real-time graphs display the shortest distance and the evolution of solutions.</li>
            </ol>
        </details>
        <details>
            <summary id="algorithms">📌 Algorithms Used</summary>
            <ul>
                <li><strong>Ant System (AS):</strong> All ants deposit pheromones equally, reinforcing shorter paths.</li>
                <li><strong>Ant Colony System (ACS):</strong> Uses pseudo-random proportional selection to balance exploration and exploitation.</li>
                <li><strong>Random System:</strong> Implements purely random movement to compare against structured ACO methods.</li>
            </ul>
        </details>
        <h2>🔗 How to Run</h2>
        <p>Simply open <code>index.html</code> in a web browser or run a local server for better performance:</p>
        <pre><code>python3 -m http.server 8000</code></pre>
        <p>Then, open <a href="http://localhost:8000/" target="_blank">http://localhost:8000/</a> in your browser.</p>
        <p>🔗 <strong>Developed with ❤️ in JavaScript by MADHAV </strong></p>
    </div>
</body>
</html>

