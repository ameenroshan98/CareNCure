<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>IGNITE'25 Leaderboard</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f4f8;
        }
        /* Ensures proper spacing between list items */
        .news-item:not(:last-child),
        .event-item:not(:last-child) {
            margin-bottom: 0.5rem;
        }
        /* Optional: Add a smooth scroll for overflow-x on touch devices */
        .overflow-x-auto {
            -webkit-overflow-scrolling: touch;
        }
    </style>
</head>
<body class="p-4 sm:p-8 flex items-center justify-center min-h-screen">
    <div class="w-full max-w-4xl bg-white rounded-xl shadow-xl overflow-hidden">

        <!-- Header Section -->
        <div class="bg-gradient-to-r from-purple-600 to-indigo-700 p-6 sm:p-8 text-white text-center rounded-t-xl">
            <h1 class="text-3xl sm:text-4xl font-bold mb-2">IGNITE'25</h1>
            <p class="text-base sm:text-lg opacity-90">Current Standings - Simple Points Accumulation</p>
        </div>

        <!-- Leaderboard Table Section -->
        <div class="p-4 sm:p-6 overflow-x-auto">
            <table class="min-w-max w-full divide-y divide-gray-200">
                <thead class="bg-gray-50 sticky top-0 z-10">
                    <tr>
                        <th class="px-2 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider rounded-tl-lg sm:px-3">Rank</th>
                        <th class="px-2 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider sm:px-3">Team</th>
                        <th class="px-2 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider sm:px-3">Points</th>
                        <th class="px-2 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider rounded-tr-lg sm:px-3 whitespace-nowrap">Last Updated</th>
                    </tr>
                </thead>
                <tbody class="bg-white divide-y divide-gray-200">
                    <!-- Team 1 -->
                    <tr class="hover:bg-purple-50">
                        <td class="px-2 py-4 text-sm font-medium text-gray-900 sm:px-3">1</td>
                        <td class="px-2 py-4 flex items-center gap-2 text-sm text-gray-700 sm:px-3">
                            <img src="https://placehold.co/24x24/facc15/a16207?text=GT" alt="Golden Titans Logo" class="w-6 h-6 rounded-full" onerror="this.onerror=null;this.src='https://placehold.co/24x24/cccccc/888888?text=TL';" />
                            Golden Titans
                        </td>
                        <td class="px-2 py-4 text-sm text-gray-700 sm:px-3">1500</td>
                        <td class="px-2 py-4 text-sm text-gray-500 sm:px-3 whitespace-nowrap">2025-06-24 10:30 AM</td>
                    </tr>
                    <!-- Team 2 -->
                    <tr class="hover:bg-purple-50">
                        <td class="px-2 py-4 text-sm font-medium text-gray-900 sm:px-3">2</td>
                        <td class="px-2 py-4 flex items-center gap-2 text-sm text-gray-700 sm:px-3">
                            <img src="https://placehold.co/24x24/1e3a8a/bfdbfe?text=VS" alt="Vortex Squad Logo" class="w-6 h-6 rounded-full" onerror="this.onerror=null;this.src='https://placehold.co/24x24/cccccc/888888?text=TL';" />
                            Vortex Squad
                        </td>
                        <td class="px-2 py-4 text-sm text-gray-700 sm:px-3">1420</td>
                        <td class="px-2 py-4 text-sm text-gray-500 sm:px-3 whitespace-nowrap">2025-06-24 11:15 AM</td>
                    </tr>
                    <!-- Team 3 -->
                    <tr class="hover:bg-purple-50">
                        <td class="px-2 py-4 text-sm font-medium text-gray-900 sm:px-3">3</td>
                        <td class="px-2 py-4 flex items-center gap-2 text-sm text-gray-700 sm:px-3">
                            <img src="https://placehold.co/24x24/dc2626/fca5a5?text=FW" alt="Flame Warriors Logo" class="w-6 h-6 rounded-full" onerror="this.onerror=null;this.src='https://placehold.co/24x24/cccccc/888888?text=TL';" />
                            Flame Warriors
                        </td>
                        <td class="px-2 py-4 text-sm text-gray-700 sm:px-3">1380</td>
                        <td class="px-2 py-4 text-sm text-gray-500 sm:px-3 whitespace-nowrap">2025-06-24 09:00 AM</td>
                    </tr>
                    <!-- Team 4 -->
                    <tr class="hover:bg-purple-50">
                        <td class="px-2 py-4 text-sm font-medium text-gray-900 sm:px-3">4</td>
                        <td class="px-2 py-4 flex items-center gap-2 text-sm text-gray-700 sm:px-3">
                            <img src="https://placehold.co/24x24/4ade80/14532d?text=PF" alt="Penta Force'25 Logo" class="w-6 h-6 rounded-full" onerror="this.onerror=null;this.src='https://placehold.co/24x24/cccccc/888888?text=TL';" />
                            Penta Force'25
                        </td>
                        <td class="px-2 py-4 text-sm text-gray-700 sm:px-3">1250</td>
                        <td class="px-2 py-4 text-sm text-gray-500 sm:px-3 whitespace-nowrap">2025-06-23 05:00 PM</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <!-- News Section -->
        <div class="bg-blue-50 border-t border-blue-200 p-4 sm:p-6">
            <h3 class="text-lg sm:text-xl font-semibold text-blue-800 mb-4 flex items-center">
                <svg class="h-6 w-6 mr-2 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v10m-3 4H7a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v10a2 2 0 01-2 2z" />
                </svg>
                Competition News & Updates
            </h3>
            <ul class="text-gray-700 text-sm sm:text-base">
                <li class="news-item">[2025-06-24] <strong>Golden Titans</strong> just crossed 1500 points! 💪</li>
                <li class="news-item">[2025-06-24] <strong>Vortex Squad</strong> secured second place after a strong challenge!</li>
                <li class="news-item">[2025-06-23] New challenge "Code Sprint" announced for tomorrow!</li>
                <li class="news-item">[2025-06-22] <strong>Flame Warriors</strong> lead in the "Problem Solving" mini-game.</li>
            </ul>
        </div>

        <!-- Events Section -->
        <div class="bg-green-50 border-t border-green-200 p-4 sm:p-6 mt-4">
            <h3 class="text-lg sm:text-xl font-semibold text-green-800 mb-4 flex items-center">
                <svg class="h-6 w-6 mr-2 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                </svg>
                Upcoming Events
            </h3>
            <ul class="text-gray-700 text-sm sm:text-base">
                <li class="event-item">[2025-07-01] Mid-Competition Check-in & Workshop</li>
                <li class="event-item">[2025-07-05] "Innovation Challenge" Deadline</li>
                <li class="event-item">[2025-07-10] Final Presentation Prep Session</li>
            </ul>
        </div>

        <!-- Footer -->
        <div class="bg-gray-100 p-4 sm:p-6 text-center text-sm text-gray-600 rounded-b-xl">
            Leaderboard updated daily. Keep earning points!<br />
            <span class="mt-1 block">Next update: 2025-06-25 09:00 AM</span>
        </div>

    </div>
</body>
</html>
