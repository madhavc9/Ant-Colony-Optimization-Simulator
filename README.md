<!DOCTYPE html>
<html lang="en">
<body>


<div align="center">
  <img src="/bg_aco.png" alt="ACO Project Logo" width="600">
  <h3 align="center">Ant Colony Optimization Simulator</h3>
  <p align="center">
   Solving complex optimization problems using the power of swarm intelligence.
    <br />
    <a href="https://drive.google.com/file/d/1qYvdLZSJQP73nDsnra9D96X2YBksIoWI/view?usp=sharing" target="_blank"><strong>Explore the documentation »</strong></a>
    <br />
    <a href="https://drive.google.com/file/d/1tP3LpOuq9oVjJ5IHTt3EekR550bA1q01/view?usp=sharing" target="_blank"><strong>Video Demonstration »</strong></a>
    <br />
    <a href="https://madhavc9.github.io/Ant-Colony-Optimization-Simulator/" target="_blank"><strong> Live Website »</strong></a>
  </p>
</div>
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
    </div>
    <div align="center">
  Developed with ❤️ in JavaScript by MADHAV
</div>
</body>
</html>

