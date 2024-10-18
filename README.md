<h1>Cybersecurity Attack Data Analysis and Visualization</h1>

<p>This project focuses on analyzing a dataset of cybersecurity attacks. It involves loading and visualizing data related to network attacks, including details like IP addresses, ports, protocols, packet length, traffic types, and user information. The project aims to provide insights into network security and the patterns of cyber attacks.</p>

<h2>Features</h2>

<ul>
  <li>Loading and preprocessing the cybersecurity attack dataset.</li>
  <li>Visualization of attack patterns using <strong>Matplotlib</strong> and <strong>Seaborn</strong>.</li>
  <li>Analysis of network traffic based on source and destination IP addresses, protocols, and packet details.</li>
  <li>Classification of actions taken (e.g., logged, blocked, ignored) and severity levels.</li>
</ul>

<h2>Dataset</h2>

<p>The project uses a dataset named <code>cybersecurity_attacks.csv</code>, which contains details about various network attacks:</p>

<ul>
  <li><strong>Timestamp</strong>: The date and time of the attack.</li>
  <li><strong>Source IP Address</strong>: The IP address from which the attack originated.</li>
  <li><strong>Destination IP Address</strong>: The target IP address of the attack.</li>
  <li><strong>Source Port</strong>: The port used by the attacker.</li>
  <li><strong>Destination Port</strong>: The target port for the attack.</li>
  <li><strong>Protocol</strong>: The network protocol used (e.g., ICMP, UDP, TCP).</li>
  <li><strong>Packet Length</strong>: Size of the packet in bytes.</li>
  <li><strong>Action Taken</strong>: Whether the attack was logged, blocked, or ignored.</li>
  <li><strong>Severity Level</strong>: The severity of the attack (e.g., low, medium, high).</li>
  <li><strong>User Information</strong>: Information about the user associated with the attack.</li>
  <li><strong>Device Information</strong>: The device details used in the attack.</li>
</ul>

<h2>Requirements</h2>

<p>To run this project, you will need the following Python libraries:</p>

<ul>
  <li><code>pandas</code></li>
  <li><code>numpy</code></li>
  <li><code>matplotlib</code></li>
  <li><code>seaborn</code></li>
</ul>

<p>Install the dependencies using:</p>

<pre><code>pip install -r requirements.txt
</code></pre>

<h2>Analysis</h2>

<p>The project analyzes attack patterns based on source and destination IPs, protocol types, and packet details. It also classifies the actions taken in response to the attacks and visualizes the distribution of different severity levels.</p>

<h2>Customization</h2>

<p>You can adjust the following aspects of the project:</p>

<ul>
  <li><strong>Dataset</strong>: Use a different cybersecurity dataset or add more fields to enhance the analysis.</li>
  <li><strong>Visualizations</strong>: Create additional visualizations, such as pie charts or heatmaps, to gain more insights into the attack data.</li>
</ul>

<h2>Acknowledgments</h2>

<ul>
  <li>Thanks to open-source Python libraries like <strong>Pandas</strong>, <strong>Matplotlib</strong>, and <strong>Seaborn</strong> for their powerful tools for data analysis and visualization.</li>
</ul>
