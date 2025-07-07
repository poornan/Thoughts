# richards-tech

\{% raw %\}

\<html lang="en">

\<head>

&#x20;   \<meta charset="UTF-8">

&#x20;   \<meta name="viewport" content="width=device-width, initial-scale=1.0">

&#x20;   \<title>The Digital Ghost & The Surviving Code: An RTIMULib Story\</title>

&#x20;   \<script src="https://cdn.tailwindcss.com">\</script>

&#x20;   \<script src="https://cdn.jsdelivr.net/npm/chart.js">\</script>

&#x20;   \<link rel="preconnect" href="https://fonts.googleapis.com">

&#x20;   \<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

&#x20;   \<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900\&display=swap" rel="stylesheet">

&#x20;   \<style>

&#x20;       body {

&#x20;           font-family: 'Inter', sans-serif;

&#x20;           background-color: #f0f4f8;

&#x20;       }

&#x20;       .chart-container {

&#x20;           position: relative;

&#x20;           width: 100%;

&#x20;           max-width: 600px;

&#x20;           margin-left: auto;

&#x20;           margin-right: auto;

&#x20;           height: 300px;

&#x20;           max-height: 400px;

&#x20;       }

&#x20;       @media (min-width: 768px) {

&#x20;           .chart-container {

&#x20;               height: 350px;

&#x20;           }

&#x20;       }

&#x20;       .flow-arrow {

&#x20;           font-size: 2rem;

&#x20;           color: #F99F20;

&#x20;           line-height: 1;

&#x20;       }

&#x20;       .timeline-item::before {

&#x20;           content: '';

&#x20;           position: absolute;

&#x20;           top: 50%;

&#x20;           left: -2.75rem;

&#x20;           transform: translateY(-50%);

&#x20;           width: 1.5rem;

&#x20;           height: 1.5rem;

&#x20;           border-radius: 50%;

&#x20;           background-color: #0582CA;

&#x20;           border: 4px solid #f0f4f8;

&#x20;       }

&#x20;       .modal {

&#x20;           transition: opacity 0.25s ease;

&#x20;       }

&#x20;       .modal-content {

&#x20;           transition: transform 0.25s ease;

&#x20;       }

&#x20;       .loader {

&#x20;           border-top-color: #0582CA;

&#x20;           animation: spin 1s linear infinite;

&#x20;       }

&#x20;       @keyframes spin {

&#x20;           to { transform: rotate(360deg); }

&#x20;       }

&#x20;   \</style>

\</head>

\<body class="text-gray-800">

\


&#x20;   \<div class="container mx-auto p-4 md:p-8">

\


&#x20;       \<header class="text-center mb-12">

&#x20;           \<h1 class="text-4xl md:text-6xl font-black text-\[#006494] uppercase tracking-wide">The Digital Ghost\</h1>

&#x20;           \<p class="text-xl md:text-2xl font-bold text-\[#00A6FB] mt-2">& The Surviving Code\</p>

&#x20;           \<p class="max-w-3xl mx-auto mt-4 text-gray-600">

&#x20;               An investigative report found that while developer \`richardstechnotes\` vanished from the web, their most influential project, \`RTIMULib\`, was saved by the open-source community. This is the story of its disappearance and digital resurrection.

&#x20;           \</p>

&#x20;       \</header>

\


&#x20;       \<section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 md:gap-8 text-center mb-12">

&#x20;           \<div class="bg-white rounded-lg shadow-md p-6">

&#x20;               \<p class="text-5xl font-black text-\[#F99F20]">2\</p>

&#x20;               \<p class="mt-2 font-bold text-gray-700">Deleted GitHub Accounts\</p>

&#x20;               \<p class="text-sm text-gray-500">\`richardstechnotes\` & \`richards-tech\`\</p>

&#x20;           \</div>

&#x20;           \<div class="bg-white rounded-lg shadow-md p-6">

&#x20;               \<p class="text-5xl font-black text-\[#F99F20]">3\</p>

&#x20;               \<p class="mt-2 font-bold text-gray-700">Unrecoverable Projects\</p>

&#x20;                \<p class="text-sm text-gray-500">\`RTNDF\`, \`manifold\`, \`RT-AI\`\</p>

&#x20;           \</div>

&#x20;           \<div class="bg-white rounded-lg shadow-md p-6">

&#x20;               \<p class="text-5xl font-black text-\[#0582CA]">1\</p>

&#x20;               \<p class="mt-2 font-bold text-gray-700">Major Surviving Legacy\</p>

&#x20;                \<p class="text-sm text-gray-500">The \`RTIMULib\` Ecosystem\</p>

&#x20;           \</div>

&#x20;           \<div class="bg-white rounded-lg shadow-md p-6">

&#x20;               \<p class="text-5xl font-black text-\[#0582CA]">100%\</p>

&#x20;               \<p class="mt-2 font-bold text-gray-700">Community Preserved\</p>

&#x20;               \<p class="text-sm text-gray-500">Kept alive through forks\</p>

&#x20;           \</div>

&#x20;       \</section>

\


&#x20;       \<main class="grid grid-cols-1 lg:grid-cols-3 gap-8">

&#x20;           \<div class="lg:col-span-3 bg-white rounded-lg shadow-md p-6">

&#x20;               \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-4">Identity Reconstruction: The Pivot to a Brand\</h2>

&#x20;               \<p class="text-center text-gray-600 max-w-2xl mx-auto mb-6">The investigation's first breakthrough was connecting the hobbyist persona to a more professional brand, which unlocked the project's history.\</p>

&#x20;               \<div class="flex items-center justify-center space-x-4 md:space-x-8">

&#x20;                   \<div class="text-center">

&#x20;                       \<div class="p-4 bg-\[#00A6FB] text-white rounded-lg shadow">

&#x20;                           \<p class="font-bold">\`richardstechnotes\`\</p>

&#x20;                           \<p class="text-xs">Initial Persona\</p>

&#x20;                       \</div>

&#x20;                   \</div>

&#x20;                   \<div class="flow-arrow font-black">→\</div>

&#x20;                   \<div class="text-center">

&#x20;                       \<div class="p-4 bg-\[#0582CA] text-white rounded-lg shadow">

&#x20;                           \<p class="font-bold">\`richards-tech\`\</p>

&#x20;                           \<p class="text-xs">Professional Brand\</p>

&#x20;                       \</div>

&#x20;                   \</div>

&#x20;               \</div>

&#x20;           \</div>

\


&#x20;           \<div class="lg:col-span-2 bg-white rounded-lg shadow-md p-6">

&#x20;                \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-4">The Legacy: \`RTIMULib\` Core Functionality\</h2>

&#x20;                \<p class="text-center text-gray-600 max-w-2xl mx-auto mb-6">\`RTIMULib\` is a powerful C++ and Python library that performs complex sensor fusion to calculate an object's real-time orientation in 3D space.\</p>

&#x20;               \<div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-4">

&#x20;                    \<div class="p-4 border-2 border-dashed border-gray-300 rounded-lg text-center">

&#x20;                       \<p class="font-bold text-\[#00A6FB]">Raw Sensor Data\</p>

&#x20;                       \<p class="text-xs text-gray-500">Accelerometer, Gyroscope, Magnetometer\</p>

&#x20;                   \</div>

&#x20;                   \<div class="flow-arrow font-black transform md:-rotate-0 rotate-90">→\</div>

&#x20;                    \<div class="p-6 bg-\[#006494] text-white rounded-full flex flex-col items-center justify-center w-40 h-40 shadow-lg">

&#x20;                       \<p class="font-black text-lg">RTQF\</p>

&#x20;                       \<p class="text-center text-xs">Custom Fusion Algorithm\</p>

&#x20;                   \</div>

&#x20;                   \<div class="flow-arrow font-black transform md:-rotate-0 rotate-90">→\</div>

&#x20;                   \<div class="p-4 border-2 border-dashed border-gray-300 rounded-lg text-center">

&#x20;                       \<p class="font-bold text-\[#00A6FB]">Stable Pose Output\</p>

&#x20;                       \<p class="text-xs text-gray-500">Quaternions & Euler Angles (Yaw, Pitch, Roll)\</p>

&#x20;                   \</div>

&#x20;               \</div>

&#x20;           \</div>

\


&#x20;           \<div class="bg-white rounded-lg shadow-md p-6">

&#x20;               \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-4">Community Preservation\</h2>

&#x20;               \<p class="text-center text-gray-600 mb-4">When the original repository was deleted, dedicated users had already created forks, ensuring the code was not lost.\</p>

&#x20;               \<div class="chart-container h-64 md:h-auto">

&#x20;                   \<canvas id="preservationChart">\</canvas>

&#x20;               \</div>

&#x20;           \</div>

\


&#x20;           \<div class="bg-white rounded-lg shadow-md p-6">

&#x20;               \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-4">Broad Hardware Support\</h2>

&#x20;               \<p class="text-center text-gray-600 mb-4">The library's popularity was driven by its compatibility with a wide range of IMU sensors from major manufacturers.\</p>

&#x20;               \<div class="chart-container">

&#x20;                   \<canvas id="hardwareSupportChart">\</canvas>

&#x20;               \</div>

&#x20;           \</div>

\


&#x20;           \<div class="lg:col-span-2 bg-white rounded-lg shadow-md p-6">

&#x20;               \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-4">Sophisticated \`RTArduLink\` Architecture\</h2>

&#x20;               \<p class="text-center text-gray-600 max-w-3xl mx-auto mb-6">A key innovation was a protocol to offload real-time sensor polling to a low-power Arduino, freeing the host system for heavy computation and visualization.\</p>

&#x20;                \<div class="flex flex-col md:flex-row items-center justify-around space-y-4 md:space-y-0">

&#x20;                   \<div class="text-center flex flex-col items-center">

&#x20;                       \<div class="p-4 bg-\[#FDCA40] text-\[#006494] rounded-lg shadow w-48">

&#x20;                           \<p class="font-bold">Arduino\</p>

&#x20;                           \<p class="text-xs">Real-time Sensor Polling\</p>

&#x20;                       \</div>

&#x20;                        \<p class="mt-2 text-xs text-gray-500">Low-power, timing-critical tasks\</p>

&#x20;                   \</div>

&#x20;                   \<div class="flex flex-col items-center text-center">

&#x20;                        \<div class="font-mono text-sm text-gray-500 p-2">USB Serial\</div>

&#x20;                        \<div class="flow-arrow font-black transform md:-rotate-0 rotate-90">→\</div>

&#x20;                        \<div class="font-mono text-sm text-gray-500 p-2">Raw Data Stream\</div>

&#x20;                   \</div>

&#x20;                   \<div class="text-center flex flex-col items-center">

&#x20;                       \<div class="p-4 bg-\[#0582CA] text-white rounded-lg shadow w-48">

&#x20;                           \<p class="font-bold">Host (PC/Raspberry Pi)\</p>

&#x20;                           \<p class="text-xs">Fusion & 3D Visualization\</p>

&#x20;                       \</div>

&#x20;                       \<p class="mt-2 text-xs text-gray-500">Computationally intensive processing\</p>

&#x20;                   \</div>

&#x20;               \</div>

&#x20;           \</div>

&#x20;          &#x20;

&#x20;           \<div class="lg:col-span-3 bg-white rounded-lg shadow-md p-6">

&#x20;               \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-6">Project Development Timeline\</h2>

&#x20;                \<div class="relative pl-12">

&#x20;                   \<div class="absolute top-0 bottom-0 left-5 border-l-4 border-\[#00A6FB]">\</div>

&#x20;                   \<div class="relative mb-8 timeline-item">

&#x20;                       \<p class="font-bold text-lg text-\[#0582CA]">April 2014\</p>

&#x20;                       \<p class="text-gray-600">Initial Release & RTQF Fusion Filter introduced\</p>

&#x20;                   \</div>

&#x20;                   \<div class="relative mb-8 timeline-item">

&#x20;                       \<p class="font-bold text-lg text-\[#0582CA]">July 2014\</p>

&#x20;                       \<p class="text-gray-600">Python Support Added\</p>

&#x20;                   \</div>

&#x20;                   \<div class="relative mb-8 timeline-item">

&#x20;                       \<p class="font-bold text-lg text-\[#0582CA]">October 2014\</p>

&#x20;                       \<p class="text-gray-600">Accelerometer Calibration Feature\</p>

&#x20;                   \</div>

&#x20;                   \<div class="relative timeline-item">

&#x20;                       \<p class="font-bold text-lg text-\[#0582CA]">2014-2015\</p>

&#x20;                       \<p class="text-gray-600">Ongoing support for new IMU and Pressure Sensors\</p>

&#x20;                   \</div>

&#x20;                \</div>

&#x20;           \</div>

\


&#x20;           \<!-- Gemini API Integration Section -->

&#x20;           \<div class="lg:col-span-3 bg-white rounded-lg shadow-md p-6">

&#x20;               \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-2">Future of RTIMULib: AI-Powered Enhancements\</h2>

&#x20;               \<p class="text-center text-gray-600 max-w-3xl mx-auto mb-6">Explore the library's potential with generative AI. Get project ideas or simplify complex topics.\</p>

&#x20;               \<div class="grid grid-cols-1 md:grid-cols-2 gap-6">

&#x20;                   \<div class="border border-gray-200 rounded-lg p-6 flex flex-col items-center text-center">

&#x20;                       \<h3 class="font-bold text-lg text-\[#006494] mb-2">Project Idea Generator\</h3>

&#x20;                       \<p class="text-gray-600 text-sm mb-4 flex-grow">Stuck for inspiration? Let AI suggest a creative project that uses \`RTIMULib\` for motion sensing.\</p>

&#x20;                       \<button id="generateProjectBtn" class="bg-\[#F99F20] text-white font-bold py-2 px-4 rounded-lg hover:bg-opacity-90 transition-colors">

&#x20;                           ✨ Suggest a Project Idea

&#x20;                       \</button>

&#x20;                   \</div>

&#x20;                   \<div class="border border-gray-200 rounded-lg p-6 flex flex-col items-center text-center">

&#x20;                       \<h3 class="font-bold text-lg text-\[#006494] mb-2">Concept Explainer\</h3>

&#x20;                       \<p class="text-gray-600 text-sm mb-4 flex-grow">Select a technical term from the infographic and get a simple, easy-to-understand explanation.\</p>

&#x20;                       \<div class="flex space-x-2">

&#x20;                            \<select id="conceptSelect" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5">

&#x20;                               \<option>Sensor Fusion\</option>

&#x20;                               \<option>Quaternion\</option>

&#x20;                               \<option>Kalman Filter\</option>

&#x20;                               \<option>IMU\</option>

&#x20;                           \</select>

&#x20;                           \<button id="explainConceptBtn" class="bg-\[#0582CA] text-white font-bold py-2 px-4 rounded-lg hover:bg-opacity-90 transition-colors">

&#x20;                               ✨ Generate Explanation

&#x20;                           \</button>

&#x20;                       \</div>

&#x20;                   \</div>

&#x20;               \</div>

&#x20;           \</div>

&#x20;       \</main>

\


&#x20;       \<footer class="mt-12 bg-white rounded-lg shadow-md p-8">

&#x20;            \<h2 class="text-2xl font-bold text-center text-\[#006494] mb-4">Recovery Protocol: Accessing The Surviving Code\</h2>

&#x20;            \<p class="text-center text-gray-600 max-w-3xl mx-auto mb-6">The \`RTIMULib\` ecosystem survives in two primary, community-maintained repositories. These are the recommended sources for obtaining the complete library.\</p>

&#x20;            \<div class="overflow-x-auto">

&#x20;               \<table class="min-w-full text-left text-sm font-light">

&#x20;                   \<thead class="border-b font-medium bg-gray-50">

&#x20;                       \<tr>

&#x20;                           \<th scope="col" class="px-6 py-4">Component\</th>

&#x20;                           \<th scope="col" class="px-6 py-4">Recommended Repository\</th>

&#x20;                           \<th scope="col" class="px-6 py-4">Primary Use Case\</th>

&#x20;                       \</tr>

&#x20;                   \</thead>

&#x20;                   \<tbody>

&#x20;                       \<tr class="border-b">

&#x20;                           \<td class="px-6 py-4 font-medium">Arduino Library\</td>

&#x20;                           \<td class="px-6 py-4 break-all">\<a href="https://github.com/luisllamasbinaburo/RTIMULib-Arduino" target="\_blank" class="text-\[#0582CA] hover:underline font-mono">luisllamasbinaburo/RTIMULib-Arduino\</a>\</td>

&#x20;                           \<td class="px-6 py-4">For all Arduino-based IMU interfacing.\</td>

&#x20;                       \</tr>

&#x20;                       \<tr class="border-b">

&#x20;                           \<td class="px-6 py-4 font-medium">Linux/Host Library\</td>

&#x20;                           \<td class="px-6 py-4 break-all">\<a href="https://github.com/RPi-Distro/RTIMULib" target="\_blank" class="text-\[#0582CA] hover:underline font-mono">RPi-Distro/RTIMULib\</a>\</td>

&#x20;                           \<td class="px-6 py-4">For Raspberry Pi, embedded Linux, or PC-based host applications.\</td>

&#x20;                       \</tr>

&#x20;                   \</tbody>

&#x20;               \</table>

&#x20;           \</div>

&#x20;       \</footer>

\


&#x20;   \</div>

\


&#x20;   \<!-- Modal -->

&#x20;   \<div id="aiModal" class="modal fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center p-4 z-50 opacity-0 pointer-events-none">

&#x20;       \<div class="modal-content bg-white rounded-lg shadow-xl w-full max-w-2xl p-6 transform scale-95">

&#x20;           \<h3 id="modalTitle" class="text-2xl font-bold text-\[#006494] mb-4">AI Generated Content\</h3>

&#x20;           \<div id="modalBody" class="text-gray-700 max-h-\[60vh] overflow-y-auto">

&#x20;               \<div class="flex justify-center items-center h-32">

&#x20;                   \<div class="loader ease-linear rounded-full border-4 border-t-4 border-gray-200 h-12 w-12">\</div>

&#x20;               \</div>

&#x20;           \</div>

&#x20;           \<div class="text-right mt-6">

&#x20;               \<button id="closeModalBtn" class="bg-gray-200 text-gray-800 font-bold py-2 px-4 rounded-lg hover:bg-gray-300 transition-colors">Close\</button>

&#x20;           \</div>

&#x20;       \</div>

&#x20;   \</div>

\


&#x20;   \<script>

&#x20;       const chartColors = {

&#x20;           blue: '#00A6FB',

&#x20;           darkBlue: '#0582CA',

&#x20;           deepBlue: '#006494',

&#x20;           orange: '#F99F20',

&#x20;           yellow: '#FDCA40',

&#x20;           grey: '#cbd5e1'

&#x20;       };

\


&#x20;       const tooltipConfig = {

&#x20;           callbacks: {

&#x20;               title: function(tooltipItems) {

&#x20;                   const item = tooltipItems\[0];

&#x20;                   let label = item.chart.data.labels\[item.dataIndex];

&#x20;                   if (Array.isArray(label)) {

&#x20;                       return label.join(' ');

&#x20;                   }

&#x20;                   return label;

&#x20;               }

&#x20;           }

&#x20;       };

\


&#x20;       function wrapLabel(str, maxWidth) {

&#x20;           if (str.length <= maxWidth) {

&#x20;               return str;

&#x20;           }

&#x20;           const words = str.split(' ');

&#x20;           let lines = \[];

&#x20;           let currentLine = '';

&#x20;           words.forEach(word => {

&#x20;               if ((currentLine + word).length > maxWidth) {

&#x20;                   lines.push(currentLine.trim());

&#x20;                   currentLine = '';

&#x20;               }

&#x20;               currentLine += word + ' ';

&#x20;           });

&#x20;           lines.push(currentLine.trim());

&#x20;           return lines.filter(line => line.length > 0);

&#x20;       }

\


&#x20;       new Chart(document.getElementById('preservationChart'), {

&#x20;           type: 'doughnut',

&#x20;           data: {

&#x20;               labels: \['Surviving Community Forks', 'Original Repo (Deleted)'],

&#x20;               datasets: \[{

&#x20;                   label: 'Repository Status',

&#x20;                   data: \[85, 15],

&#x20;                   backgroundColor: \[chartColors.darkBlue, chartColors.grey],

&#x20;                   borderColor: '#ffffff',

&#x20;                   borderWidth: 4,

&#x20;               }]

&#x20;           },

&#x20;           options: {

&#x20;               responsive: true,

&#x20;               maintainAspectRatio: false,

&#x20;               plugins: {

&#x20;                   legend: {

&#x20;                       position: 'bottom',

&#x20;                   },

&#x20;                   tooltip: tooltipConfig,

&#x20;               },

&#x20;               cutout: '70%'

&#x20;           }

&#x20;       });

\


&#x20;       new Chart(document.getElementById('hardwareSupportChart'), {

&#x20;           type: 'bar',

&#x20;           data: {

&#x20;               labels: \['InvenSense', 'STM', 'Bosch'],

&#x20;               datasets: \[{

&#x20;                   label: 'Supported Chips Mentioned',

&#x20;                   data: \[2, 2, 1],

&#x20;                   backgroundColor: \[chartColors.blue, chartColors.darkBlue, chartColors.deepBlue],

&#x20;                   borderRadius: 4

&#x20;               }]

&#x20;           },

&#x20;           options: {

&#x20;               responsive: true,

&#x20;               maintainAspectRatio: false,

&#x20;               indexAxis: 'y',

&#x20;               scales: {

&#x20;                   x: {

&#x20;                       beginAtZero: true,

&#x20;                       grid: { display: false },

&#x20;                       ticks: { stepSize: 1 }

&#x20;                   },

&#x20;                   y: {

&#x20;                       grid: { display: false }

&#x20;                   }

&#x20;               },

&#x20;               plugins: {

&#x20;                   legend: {

&#x20;                       display: false

&#x20;                   },

&#x20;                   tooltip: tooltipConfig,

&#x20;               }

&#x20;           }

&#x20;       });

\


&#x20;       // Gemini API Integration

&#x20;       const modal = document.getElementById('aiModal');

&#x20;       const modalTitle = document.getElementById('modalTitle');

&#x20;       const modalBody = document.getElementById('modalBody');

&#x20;       const closeModalBtn = document.getElementById('closeModalBtn');

&#x20;       const generateProjectBtn = document.getElementById('generateProjectBtn');

&#x20;       const explainConceptBtn = document.getElementById('explainConceptBtn');

&#x20;       const conceptSelect = document.getElementById('conceptSelect');

\


&#x20;       const loadingSpinner = \`\<div class="flex justify-center items-center h-32">\<div class="loader ease-linear rounded-full border-4 border-t-4 border-gray-200 h-12 w-12">\</div>\</div>\`;

\


&#x20;       function openModal() {

&#x20;           modal.classList.remove('opacity-0', 'pointer-events-none');

&#x20;           modal.querySelector('.modal-content').classList.remove('scale-95');

&#x20;       }

\


&#x20;       function closeModal() {

&#x20;           modal.classList.add('opacity-0', 'pointer-events-none');

&#x20;           modal.querySelector('.modal-content').classList.add('scale-95');

&#x20;       }

\


&#x20;       closeModalBtn.addEventListener('click', closeModal);

&#x20;       modal.addEventListener('click', (e) => {

&#x20;           if (e.target === modal) {

&#x20;               closeModal();

&#x20;           }

&#x20;       });

\


&#x20;       async function callGeminiAPI(prompt) {

&#x20;           const apiKey = ""; // API key is handled by the environment

&#x20;           const apiUrl = \`https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}\`;

&#x20;          &#x20;

&#x20;           const payload = {

&#x20;               contents: \[{ role: "user", parts: \[{ text: prompt }] }]

&#x20;           };

\


&#x20;           try {

&#x20;               const response = await fetch(apiUrl, {

&#x20;                   method: 'POST',

&#x20;                   headers: { 'Content-Type': 'application/json' },

&#x20;                   body: JSON.stringify(payload)

&#x20;               });

\


&#x20;               if (!response.ok) {

&#x20;                   throw new Error(\`API call failed with status: ${response.status}\`);

&#x20;               }

\


&#x20;               const result = await response.json();

&#x20;              &#x20;

&#x20;               if (result.candidates && result.candidates.length > 0 &&

&#x20;                   result.candidates\[0].content && result.candidates\[0].content.parts &&

&#x20;                   result.candidates\[0].content.parts.length > 0) {

&#x20;                   return result.candidates\[0].content.parts\[0].text;

&#x20;               } else {

&#x20;                   return "Sorry, I couldn't generate a response. The AI model returned an unexpected result.";

&#x20;               }

&#x20;           } catch (error) {

&#x20;               console.error("Error calling Gemini API:", error);

&#x20;               return \`Sorry, an error occurred while contacting the AI model: ${error.message}. Please check the console for details.\`;

&#x20;           }

&#x20;       }

\


&#x20;       generateProjectBtn.addEventListener('click', async () => {

&#x20;           modalTitle.textContent = 'AI-Generated Project Idea';

&#x20;           modalBody.innerHTML = loadingSpinner;

&#x20;           openModal();

\


&#x20;           const prompt = "You are an expert in robotics and creative technology. Based on the RTIMULib library, which is used for real-time sensor fusion with IMUs (accelerometers, gyroscopes) to get object orientation (quaternions, yaw, pitch, roll), suggest one creative and detailed project idea. The idea should be suitable for a hobbyist. Describe the project, the key components needed, and the role RTIMULib would play. Format the response in Markdown with headings.";

&#x20;          &#x20;

&#x20;           const responseText = await callGeminiAPI(prompt);

&#x20;           modalBody.innerHTML = responseText.replace(/\n/g, '\<br>'); // Basic markdown to HTML

&#x20;       });

\


&#x20;       explainConceptBtn.addEventListener('click', async () => {

&#x20;           const concept = conceptSelect.value;

&#x20;           modalTitle.textContent = \`Explanation of ${concept}\`;

&#x20;           modalBody.innerHTML = loadingSpinner;

&#x20;           openModal();

\


&#x20;           const prompt = \`Explain the concept of "${concept}" in simple terms, as you would to a beginner in electronics and programming. Keep the explanation concise (2-3 paragraphs) and use an analogy if possible. The context is its use in IMU sensor fusion for projects like drones or robotics.\`;

&#x20;          &#x20;

&#x20;           const responseText = await callGeminiAPI(prompt);

&#x20;           modalBody.innerHTML = responseText.replace(/\n/g, '\<br>');

&#x20;       });

\


&#x20;   \</script>

\


\</body>

\</html>

\{% endraw %\}
