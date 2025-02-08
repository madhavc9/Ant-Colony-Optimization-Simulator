<!DOCTYPE html>
<html lang="en">
<body>
    <div class="container">
        <h1>Ant Colony Optimization Simulator</h1>
        <p><em>Solving complex optimization problems using the power of swarm intelligence.</em></p>    
        <details>
            <summary>Table of Contents</summary>
            <br>
            <ul>
                <li><a href="#introduction">Introduction</a></li>
                <li><a href="#technologies">Technologies Used</a></li>
                <li><a href="#working">Working</a></li>
                <li><a href="#algorithms">Algorithms Used</a></li>
                <li><a href="#how-to-run">How to Run</a></li>
            </ul>
        </details>
        <hr>
        <details>
            <summary id="introduction">Introduction</summary>
            <br>
            <p>The <strong>Ant Colony Optimization Simulator</strong> is a web-based tool that simulates the behavior of ants to solve optimization problems such as the <strong>Traveling Salesman Problem (TSP)</strong>. It visualizes how artificial ants traverse paths, deposit pheromones, and iteratively improve solutions to find the shortest route between multiple nodes.</p>
        </details>
        <hr>  
        <details>
            <summary id="technologies">Technologies Used</summary>
            <br>
            <ul>
                <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
                <li><strong>Visualization:</strong> Fabric.js for rendering nodes and paths</li>
                <li><strong>Data Handling:</strong> CSV parsing for node coordinates</li>
                <li><strong>Graph Plotting:</strong> Chart.js for real-time distance tracking</li>
                <li><strong>Utilities:</strong> Various JavaScript helper functions for algorithm implementation</li>
            </ul>
        </details>
       <hr>
        <details>
            <summary id="working">Working</summary>
            <br>
            <ol>
                <li><strong>User Input:</strong> Nodes (locations) are added manually or loaded via CSV files.</li>
                <li><strong>Simulation Start:</strong> Ants move between nodes based on pheromone trails and heuristic information.</li>
                <li><strong>Pheromone Update:</strong> After each iteration, pheromones evaporate and get reinforced on shorter paths.</li>
                <li><strong>Path Optimization:</strong> The algorithm refines the path selection over multiple generations.</li>
                <li><strong>Visualization:</strong> Real-time graphs display the shortest distance and the evolution of solutions.</li>
            </ol>
        </details>
    <hr>
        <details>
            <summary id="algorithms">Algorithms Used</summary>
            <br>
            <ul>
                <li><strong>Ant System (AS):</strong> All ants deposit pheromones equally, reinforcing shorter paths.</li>
                <li><strong>Ant Colony System (ACS):</strong> Uses pseudo-random proportional selection to balance exploration and exploitation.</li>
                <li><strong>Random System:</strong> Implements purely random movement to compare against structured ACO methods.</li>
            </ul>
        </details>
       <hr>
        <details>
            <summary id="how-to-run">How to Run</summary>
            <br>
            <p>Simply open <code>index.html</code> in any web browser to start the simulation. No additional setup or server is required.</p>
        </details>
        <hr>
        <p><strong>Developed with ❤️ in JavaScript by MADHAV</strong></p>
    </div>
</body>
</html>

