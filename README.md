<!DOCTYPE html>
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
    .news-item:not(:last-child),
    .event-item:not(:last-child) {
      margin-bottom: 0.5rem;
    }
  </style>
</head>
<body class="p-4 sm:p-8 flex items-center justify-center min-h-screen">
  <div class="w-full max-w-4xl bg-white rounded-xl shadow-xl overflow-hidden">
    
    <!-- Header -->
    <div class="bg-gradient-to-r from-purple-600 to-indigo-700 p-6 sm:p-8 text-white text-center rounded-t-xl">
      <h1 class="text-3xl sm:text-4xl font-bold mb-2">IGNITE'25</h1>
      <p class="text-lg opacity-90">Current Standings - Simple Points Accumulation</p>
    </div>

    <!-- Leaderboard -->
    <div class="p-4 sm:p-6 overflow-x-auto">
      <table class="min-w-full divide-y divide-gray-200">
        <thead class="bg-gray-50 sticky top-0 z-10">
          <tr>
            <th class="px-3 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider rounded-tl-lg">Rank</th>
            <th class="px-3 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Team</th>
            <th class="px-3 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Points</th>
            <th class="px-3 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider rounded-tr-lg">Last Updated</th>
          </tr>
        </thead>
        <tbody class="bg-white divide-y divide-gray-200">
          <tr class="hover:bg-purple-50">
            <td class="px-3 py-4 text-sm font-medium text-gray-900">1</td>
            <td class="px-3 py-4 flex items-center gap-2 text-sm text-gray-700">
              <img src="images/golden-titans.png" alt="Golden Titans Logo" class="w-6 h-6 rounded-full" />
              Golden Titans
            </td>
            <td class="px-3 py-4 text-sm text-gray-700">1500</td>
            <td class="px-3 py-4 text-sm text-gray-500">2025-06-24 10:30 AM</td>
          </tr>
          <!-- Add more teams here -->
        </tbody>
      </table>
    </div>

    <!-- News Section -->
    <div class="bg-blue-50 border-t border-blue-200 p-4 sm:p-6">
      <h3 class="text-xl font-semibold text-blue-800 mb-4 flex items-center">
        <svg class="h-6 w-6 mr-2 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v10m-3 4H7a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v10a2 2 0 01-2 2z" />
        </svg>
        Competition News & Updates
      </h3>
      <ul class="text-gray-700 text-sm sm:text-base">
        <li class="news-item">[2025-06-24] <strong>Golden Titans</strong> just crossed 1500 points! 💪</li>
        <!-- Add more news -->
      </ul>
    </div>

    <!-- Events Section -->
    <div class="bg-green-50 border-t border-green-200 p-4 sm:p-6 mt-4">
      <h3 class="text-xl font-semibold text-green-800 mb-4 flex items-center">
        <svg class="h-6 w-6 mr-2 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
        </svg>
        Upcoming Events
      </h3>
      <ul class="text-gray-700 text-sm sm:text-base">
        <li class="event-item">[2025-07-01] Mid-Competition Check-in & Workshop</li>
        <!-- Add more events -->
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
