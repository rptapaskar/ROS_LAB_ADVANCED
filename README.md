# ROS 2 Mobile Robotics Laboratory — Interactive Website

This folder is ready to deploy as a static site using **GitHub Pages**.

## Landing page
`index.html` is the landing page for the complete laboratory. It links to Experiments 01–11.

## Experiments
- `exp01.html` — Meet the Robot + Linux
- `exp02.html` — ROS 2: From Command to Robot Motion
- `exp03.html` — ROS 2 Multi-Sensor Interfacing
- `exp04.html` — Differential Drive Kinematics + Odometry
- `exp05.html` — LiDAR Obstacle Detection + Reactive Navigation
- `exp06.html` — RGB-D Depth Perception + Vision Control
- `exp07.html` — Odometry Accuracy + Drift
- `exp08.html` — LiDAR vs RGB-D Comparative Ranging
- `exp09.html` — Sensor Fusion + Localisation
- `exp10.html` — Design Your Own Local Navigator
- `exp11.html` — Autonomous Mobile Robot Application using SLAM + Nav2

## Deploy on GitHub Pages
1. Create a GitHub repository.
2. Upload **all files in this folder** to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and the `/ (root)` folder, then save.
6. GitHub Pages will publish `index.html` as the site home page.

No server, Node.js, Python or build step is required; the pages are self-contained HTML files.
