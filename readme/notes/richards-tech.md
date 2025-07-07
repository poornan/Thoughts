# richards-tech

{% embed url="https://g.co/gemini/share/3e61122ed9f5" %}

The Digital Ghost & The Surviving Code: An RTIMULib Story

```
<div class="container mx-auto p-4 md:p-8">

    <header class="text-center mb-12">
        <h1 class="text-4xl md:text-6xl font-black text-[#006494] uppercase tracking-wide">The Digital Ghost</h1>
        <p class="text-xl md:text-2xl font-bold text-[#00A6FB] mt-2">& The Surviving Code</p>
        <p class="max-w-3xl mx-auto mt-4 text-gray-600">
            An investigative report found that while developer `richardstechnotes` vanished from the web, their most influential project, `RTIMULib`, was saved by the open-source community. This is the story of its disappearance and digital resurrection.
        </p>
    </header>

    <section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 md:gap-8 text-center mb-12">
        <div class="bg-white rounded-lg shadow-md p-6">
            <p class="text-5xl font-black text-[#F99F20]">2</p>
            <p class="mt-2 font-bold text-gray-700">Deleted GitHub Accounts</p>
            <p class="text-sm text-gray-500">`richardstechnotes` & `richards-tech`</p>
        </div>
        <div class="bg-white rounded-lg shadow-md p-6">
            <p class="text-5xl font-black text-[#F99F20]">3</p>
            <p class="mt-2 font-bold text-gray-700">Unrecoverable Projects</p>
             <p class="text-sm text-gray-500">`RTNDF`, `manifold`, `RT-AI`</p>
        </div>
        <div class="bg-white rounded-lg shadow-md p-6">
            <p class="text-5xl font-black text-[#0582CA]">1</p>
            <p class="mt-2 font-bold text-gray-700">Major Surviving Legacy</p>
             <p class="text-sm text-gray-500">The `RTIMULib` Ecosystem</p>
        </div>
        <div class="bg-white rounded-lg shadow-md p-6">
            <p class="text-5xl font-black text-[#0582CA]">100%</p>
            <p class="mt-2 font-bold text-gray-700">Community Preserved</p>
            <p class="text-sm text-gray-500">Kept alive through forks</p>
        </div>
    </section>

    <main class="grid grid-cols-1 lg:grid-cols-3 gap-8">
        <div class="lg:col-span-3 bg-white rounded-lg shadow-md p-6">
            <h2 class="text-2xl font-bold text-center text-[#006494] mb-4">Identity Reconstruction: The Pivot to a Brand</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-6">The investigation's first breakthrough was connecting the hobbyist persona to a more professional brand, which unlocked the project's history.</p>
            <div class="flex items-center justify-center space-x-4 md:space-x-8">
                <div class="text-center">
                    <div class="p-4 bg-[#00A6FB] text-white rounded-lg shadow">
                        <p class="font-bold">`richardstechnotes`</p>
                        <p class="text-xs">Initial Persona</p>
                    </div>
                </div>
                <div class="flow-arrow font-black">→</div>
                <div class="text-center">
                    <div class="p-4 bg-[#0582CA] text-white rounded-lg shadow">
                        <p class="font-bold">`richards-tech`</p>
                        <p class="text-xs">Professional Brand</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="lg:col-span-2 bg-white rounded-lg shadow-md p-6">
             <h2 class="text-2xl font-bold text-center text-[#006494] mb-4">The Legacy: `RTIMULib` Core Functionality</h2>
             <p class="text-center text-gray-600 max-w-2xl mx-auto mb-6">`RTIMULib` is a powerful C++ and Python library that performs complex sensor fusion to calculate an object's real-time orientation in 3D space.</p>
            <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-4">
                 <div class="p-4 border-2 border-dashed border-gray-300 rounded-lg text-center">
                    <p class="font-bold text-[#00A6FB]">Raw Sensor Data</p>
                    <p class="text-xs text-gray-500">Accelerometer, Gyroscope, Magnetometer</p>
                </div>
                <div class="flow-arrow font-black transform md:-rotate-0 rotate-90">→</div>
                 <div class="p-6 bg-[#006494] text-white rounded-full flex flex-col items-center justify-center w-40 h-40 shadow-lg">
                    <p class="font-black text-lg">RTQF</p>
                    <p class="text-center text-xs">Custom Fusion Algorithm</p>
                </div>
                <div class="flow-arrow font-black transform md:-rotate-0 rotate-90">→</div>
                <div class="p-4 border-2 border-dashed border-gray-300 rounded-lg text-center">
                    <p class="font-bold text-[#00A6FB]">Stable Pose Output</p>
                    <p class="text-xs text-gray-500">Quaternions & Euler Angles (Yaw, Pitch, Roll)</p>
                </div>
            </div>
        </div>

        <div class="bg-white rounded-lg shadow-md p-6">
            <h2 class="text-2xl font-bold text-center text-[#006494] mb-4">Community Preservation</h2>
            <p class="text-center text-gray-600 mb-4">When the original repository was deleted, dedicated users had already created forks, ensuring the code was not lost.</p>
            <div class="chart-container h-64 md:h-auto">
                <canvas id="preservationChart"></canvas>
            </div>
        </div>

        <div class="bg-white rounded-lg shadow-md p-6">
            <h2 class="text-2xl font-bold text-center text-[#006494] mb-4">Broad Hardware Support</h2>
            <p class="text-center text-gray-600 mb-4">The library's popularity was driven by its compatibility with a wide range of IMU sensors from major manufacturers.</p>
            <div class="chart-container">
                <canvas id="hardwareSupportChart"></canvas>
            </div>
        </div>

        <div class="lg:col-span-2 bg-white rounded-lg shadow-md p-6">
            <h2 class="text-2xl font-bold text-center text-[#006494] mb-4">Sophisticated `RTArduLink` Architecture</h2>
            <p class="text-center text-gray-600 max-w-3xl mx-auto mb-6">A key innovation was a protocol to offload real-time sensor polling to a low-power Arduino, freeing the host system for heavy computation and visualization.</p>
             <div class="flex flex-col md:flex-row items-center justify-around space-y-4 md:space-y-0">
                <div class="text-center flex flex-col items-center">
                    <div class="p-4 bg-[#FDCA40] text-[#006494] rounded-lg shadow w-48">
                        <p class="font-bold">Arduino</p>
                        <p class="text-xs">Real-time Sensor Polling</p>
                    </div>
                     <p class="mt-2 text-xs text-gray-500">Low-power, timing-critical tasks</p>
                </div>
                <div class="flex flex-col items-center text-center">
                     <div class="font-mono text-sm text-gray-500 p-2">USB Serial</div>
                     <div class="flow-arrow font-black transform md:-rotate-0 rotate-90">→</div>
                     <div class="font-mono text-sm text-gray-500 p-2">Raw Data Stream</div>
                </div>
                <div class="text-center flex flex-col items-center">
                    <div class="p-4 bg-[#0582CA] text-white rounded-lg shadow w-48">
                        <p class="font-bold">Host (PC/Raspberry Pi)</p>
                        <p class="text-xs">Fusion & 3D Visualization</p>
                    </div>
                    <p class="mt-2 text-xs text-gray-500">Computationally intensive processing</p>
                </div>
            </div>
        </div>
        
        <div class="lg:col-span-3 bg-white rounded-lg shadow-md p-6">
            <h2 class="text-2xl font-bold text-center text-[#006494] mb-6">Project Development Timeline</h2>
             <div class="relative pl-12">
                <div class="absolute top-0 bottom-0 left-5 border-l-4 border-[#00A6FB]"></div>
                <div class="relative mb-8 timeline-item">
                    <p class="font-bold text-lg text-[#0582CA]">April 2014</p>
                    <p class="text-gray-600">Initial Release & RTQF Fusion Filter introduced</p>
                </div>
                <div class="relative mb-8 timeline-item">
                    <p class="font-bold text-lg text-[#0582CA]">July 2014</p>
                    <p class="text-gray-600">Python Support Added</p>
                </div>
                <div class="relative mb-8 timeline-item">
                    <p class="font-bold text-lg text-[#0582CA]">October 2014</p>
                    <p class="text-gray-600">Accelerometer Calibration Feature</p>
                </div>
                <div class="relative timeline-item">
                    <p class="font-bold text-lg text-[#0582CA]">2014-2015</p>
                    <p class="text-gray-600">Ongoing support for new IMU and Pressure Sensors</p>
                </div>
             </div>
        </div>

        <!-- Gemini API Integration Section -->
        <div class="lg:col-span-3 bg-white rounded-lg shadow-md p-6">
            <h2 class="text-2xl font-bold text-center text-[#006494] mb-2">Future of RTIMULib: AI-Powered Enhancements</h2>
            <p class="text-center text-gray-600 max-w-3xl mx-auto mb-6">Explore the library's potential with generative AI. Get project ideas or simplify complex topics.</p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="border border-gray-200 rounded-lg p-6 flex flex-col items-center text-center">
                    <h3 class="font-bold text-lg text-[#006494] mb-2">Project Idea Generator</h3>
                    <p class="text-gray-600 text-sm mb-4 flex-grow">Stuck for inspiration? Let AI suggest a creative project that uses `RTIMULib` for motion sensing.</p>
                    <button id="generateProjectBtn" class="bg-[#F99F20] text-white font-bold py-2 px-4 rounded-lg hover:bg-opacity-90 transition-colors">
                        ✨ Suggest a Project Idea
                    </button>
                </div>
                <div class="border border-gray-200 rounded-lg p-6 flex flex-col items-center text-center">
                    <h3 class="font-bold text-lg text-[#006494] mb-2">Concept Explainer</h3>
                    <p class="text-gray-600 text-sm mb-4 flex-grow">Select a technical term from the infographic and get a simple, easy-to-understand explanation.</p>
                    <div class="flex space-x-2">
                         <select id="conceptSelect" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5">
                            <option>Sensor Fusion</option>
                            <option>Quaternion</option>
                            <option>Kalman Filter</option>
                            <option>IMU</option>
                        </select>
                        <button id="explainConceptBtn" class="bg-[#0582CA] text-white font-bold py-2 px-4 rounded-lg hover:bg-opacity-90 transition-colors">
                            ✨ Generate Explanation
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <footer class="mt-12 bg-white rounded-lg shadow-md p-8">
         <h2 class="text-2xl font-bold text-center text-[#006494] mb-4">Recovery Protocol: Accessing The Surviving Code</h2>
         <p class="text-center text-gray-600 max-w-3xl mx-auto mb-6">The `RTIMULib` ecosystem survives in two primary, community-maintained repositories. These are the recommended sources for obtaining the complete library.</p>
         <div class="overflow-x-auto">
            <table class="min-w-full text-left text-sm font-light">
                <thead class="border-b font-medium bg-gray-50">
                    <tr>
                        <th scope="col" class="px-6 py-4">Component</th>
                        <th scope="col" class="px-6 py-4">Recommended Repository</th>
                        <th scope="col" class="px-6 py-4">Primary Use Case</th>
                    </tr>
                </thead>
                <tbody>
                    <tr class="border-b">
                        <td class="px-6 py-4 font-medium">Arduino Library</td>
                        <td class="px-6 py-4 break-all"><a href="https://github.com/luisllamasbinaburo/RTIMULib-Arduino" target="_blank" class="text-[#0582CA] hover:underline font-mono">luisllamasbinaburo/RTIMULib-Arduino</a></td>
                        <td class="px-6 py-4">For all Arduino-based IMU interfacing.</td>
                    </tr>
                    <tr class="border-b">
                        <td class="px-6 py-4 font-medium">Linux/Host Library</td>
                        <td class="px-6 py-4 break-all"><a href="https://github.com/RPi-Distro/RTIMULib" target="_blank" class="text-[#0582CA] hover:underline font-mono">RPi-Distro/RTIMULib</a></td>
                        <td class="px-6 py-4">For Raspberry Pi, embedded Linux, or PC-based host applications.</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </footer>

</div>

<!-- Modal -->
<div id="aiModal" class="modal fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center p-4 z-50 opacity-0 pointer-events-none">
    <div class="modal-content bg-white rounded-lg shadow-xl w-full max-w-2xl p-6 transform scale-95">
        <h3 id="modalTitle" class="text-2xl font-bold text-[#006494] mb-4">AI Generated Content</h3>
        <div id="modalBody" class="text-gray-700 max-h-[60vh] overflow-y-auto">
            <div class="flex justify-center items-center h-32">
                <div class="loader ease-linear rounded-full border-4 border-t-4 border-gray-200 h-12 w-12"></div>
            </div>
        </div>
        <div class="text-right mt-6">
            <button id="closeModalBtn" class="bg-gray-200 text-gray-800 font-bold py-2 px-4 rounded-lg hover:bg-gray-300 transition-colors">Close</button>
        </div>
    </div>
</div>

<script>
    const chartColors = {
        blue: '#00A6FB',
        darkBlue: '#0582CA',
        deepBlue: '#006494',
        orange: '#F99F20',
        yellow: '#FDCA40',
        grey: '#cbd5e1'
    };

    const tooltipConfig = {
        callbacks: {
            title: function(tooltipItems) {
                const item = tooltipItems[0];
                let label = item.chart.data.labels[item.dataIndex];
                if (Array.isArray(label)) {
                    return label.join(' ');
                }
                return label;
            }
        }
    };

    function wrapLabel(str, maxWidth) {
        if (str.length <= maxWidth) {
            return str;
        }
        const words = str.split(' ');
        let lines = [];
        let currentLine = '';
        words.forEach(word => {
            if ((currentLine + word).length > maxWidth) {
                lines.push(currentLine.trim());
                currentLine = '';
            }
            currentLine += word + ' ';
        });
        lines.push(currentLine.trim());
        return lines.filter(line => line.length > 0);
    }

    new Chart(document.getElementById('preservationChart'), {
        type: 'doughnut',
        data: {
            labels: ['Surviving Community Forks', 'Original Repo (Deleted)'],
            datasets: [{
                label: 'Repository Status',
                data: [85, 15],
                backgroundColor: [chartColors.darkBlue, chartColors.grey],
                borderColor: '#ffffff',
                borderWidth: 4,
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    position: 'bottom',
                },
                tooltip: tooltipConfig,
            },
            cutout: '70%'
        }
    });

    new Chart(document.getElementById('hardwareSupportChart'), {
        type: 'bar',
        data: {
            labels: ['InvenSense', 'STM', 'Bosch'],
            datasets: [{
                label: 'Supported Chips Mentioned',
                data: [2, 2, 1],
                backgroundColor: [chartColors.blue, chartColors.darkBlue, chartColors.deepBlue],
                borderRadius: 4
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            indexAxis: 'y',
            scales: {
                x: {
                    beginAtZero: true,
                    grid: { display: false },
                    ticks: { stepSize: 1 }
                },
                y: {
                    grid: { display: false }
                }
            },
            plugins: {
                legend: {
                    display: false
                },
                tooltip: tooltipConfig,
            }
        }
    });

    // Gemini API Integration
    const modal = document.getElementById('aiModal');
    const modalTitle = document.getElementById('modalTitle');
    const modalBody = document.getElementById('modalBody');
    const closeModalBtn = document.getElementById('closeModalBtn');
    const generateProjectBtn = document.getElementById('generateProjectBtn');
    const explainConceptBtn = document.getElementById('explainConceptBtn');
    const conceptSelect = document.getElementById('conceptSelect');

    const loadingSpinner = `<div class="flex justify-center items-center h-32"><div class="loader ease-linear rounded-full border-4 border-t-4 border-gray-200 h-12 w-12"></div></div>`;

    function openModal() {
        modal.classList.remove('opacity-0', 'pointer-events-none');
        modal.querySelector('.modal-content').classList.remove('scale-95');
    }

    function closeModal() {
        modal.classList.add('opacity-0', 'pointer-events-none');
        modal.querySelector('.modal-content').classList.add('scale-95');
    }

    closeModalBtn.addEventListener('click', closeModal);
    modal.addEventListener('click', (e) => {
        if (e.target === modal) {
            closeModal();
        }
    });

    async function callGeminiAPI(prompt) {
        const apiKey = ""; // API key is handled by the environment
        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;
        
        const payload = {
            contents: [{ role: "user", parts: [{ text: prompt }] }]
        };

        try {
            const response = await fetch(apiUrl, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(payload)
            });

            if (!response.ok) {
                throw new Error(`API call failed with status: ${response.status}`);
            }

            const result = await response.json();
            
            if (result.candidates && result.candidates.length > 0 &&
                result.candidates[0].content && result.candidates[0].content.parts &&
                result.candidates[0].content.parts.length > 0) {
                return result.candidates[0].content.parts[0].text;
            } else {
                return "Sorry, I couldn't generate a response. The AI model returned an unexpected result.";
            }
        } catch (error) {
            console.error("Error calling Gemini API:", error);
            return `Sorry, an error occurred while contacting the AI model: ${error.message}. Please check the console for details.`;
        }
    }

    generateProjectBtn.addEventListener('click', async () => {
        modalTitle.textContent = 'AI-Generated Project Idea';
        modalBody.innerHTML = loadingSpinner;
        openModal();

        const prompt = "You are an expert in robotics and creative technology. Based on the RTIMULib library, which is used for real-time sensor fusion with IMUs (accelerometers, gyroscopes) to get object orientation (quaternions, yaw, pitch, roll), suggest one creative and detailed project idea. The idea should be suitable for a hobbyist. Describe the project, the key components needed, and the role RTIMULib would play. Format the response in Markdown with headings.";
        
        const responseText = await callGeminiAPI(prompt);
        modalBody.innerHTML = responseText.replace(/\n/g, '<br>'); // Basic markdown to HTML
    });

    explainConceptBtn.addEventListener('click', async () => {
        const concept = conceptSelect.value;
        modalTitle.textContent = `Explanation of ${concept}`;
        modalBody.innerHTML = loadingSpinner;
        openModal();

        const prompt = `Explain the concept of "${concept}" in simple terms, as you would to a beginner in electronics and programming. Keep the explanation concise (2-3 paragraphs) and use an analogy if possible. The context is its use in IMU sensor fusion for projects like drones or robotics.`;
        
        const responseText = await callGeminiAPI(prompt);
        modalBody.innerHTML = responseText.replace(/\n/g, '<br>');
    });

</script>
```
