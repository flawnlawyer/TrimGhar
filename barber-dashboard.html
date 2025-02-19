<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TRIMGHAR - Barber Dashboard</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Include Chart.js library -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body class="bg-gray-100">
  <!-- Navigation Header -->
  <header class="bg-green-600 text-white p-4 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-xl font-bold">TRIMGHAR - Barber Dashboard</h1>
      <nav>
        <a href="trim.html" class="hover:underline">Home</a>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main class="container mx-auto p-6">
    <!-- Analytics Section -->
    <section class="mb-8">
      <h2 class="text-2xl font-semibold text-gray-800 mb-4 text-center">Analytics</h2>
      <div class="bg-white shadow rounded-lg p-6">
        <div class="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
          <div class="mb-4 md:mb-0">
            <label for="analyticsDate" class="block text-gray-700 mb-2">Select Date</label>
            <input
              type="date"
              id="analyticsDate"
              name="analyticsDate"
              class="w-full md:w-auto px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600"
            />
          </div>
          <div>
            <button id="getAnalytics" type="button" class="bg-green-500 text-white px-4 py-2 rounded-lg hover:bg-green-700 transition">
              Get Analytics
            </button>
          </div>
        </div>
        <!-- Chart Containers -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-6">
          <!-- Appointments Chart -->
          <div class="bg-gray-50 p-4 rounded-lg shadow">
            <h3 class="text-xl font-semibold text-gray-800 mb-2 text-center">Appointments</h3>
            <canvas id="appointmentsChart"></canvas>
          </div>
          <!-- Revenue Chart -->
          <div class="bg-gray-50 p-4 rounded-lg shadow">
            <h3 class="text-xl font-semibold text-gray-800 mb-2 text-center">Revenue</h3>
            <canvas id="revenueChart"></canvas>
          </div>
        </div>
      </div>
    </section>

    <!-- Schedule Management Section -->
    <section>
      <h2 class="text-2xl font-semibold text-gray-800 mb-4 text-center">Manage Your Schedule</h2>
      <form class="bg-white p-6 rounded-lg shadow-md max-w-lg mx-auto">
        <div class="mb-4">
          <label class="block text-gray-700 mb-2" for="openingTime">Opening Time</label>
          <input
            type="time"
            id="openingTime"
            name="openingTime"
            class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600"
            required
          />
        </div>
        <div class="mb-4">
          <label class="block text-gray-700 mb-2" for="closingTime">Closing Time</label>
          <input
            type="time"
            id="closingTime"
            name="closingTime"
            class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600"
            required
          />
        </div>
        <div class="mb-4">
          <label class="block text-gray-700 mb-2" for="bookingSlots">Available Booking Slots</label>
          <input
            type="text"
            id="bookingSlots"
            name="bookingSlots"
            placeholder="Enter time slots separated by commas (e.g., 10:00, 11:00, 12:00)"
            class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600"
            required
          />
        </div>
        <div class="text-center">
          <button type="submit" class="bg-green-500 text-white px-6 py-2 rounded-lg hover:bg-green-700 transition">
            Update Schedule
          </button>
        </div>
      </form>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-green-600 text-white p-4 text-center mt-8">
    &copy; 2025 TRIMGHAR. All rights reserved.
  </footer>

  <!-- Chart.js initialization script -->
  <script>
    // Dummy data for the appointments chart
    const appointmentsData = {
      labels: ['10:00', '11:00', '12:00', '13:00', '14:00'],
      datasets: [{
        label: 'Appointments',
        data: [2, 3, 5, 1, 4],
        backgroundColor: 'rgba(34, 197, 94, 0.7)',
        borderColor: 'rgba(34, 197, 94, 1)',
        borderWidth: 1
      }]
    };

    // Dummy data for the revenue chart
    const revenueData = {
      labels: ['10:00', '11:00', '12:00', '13:00', '14:00'],
      datasets: [{
        label: 'Revenue ($)',
        data: [100, 150, 200, 80, 120],
        backgroundColor: 'rgba(59, 130, 246, 0.7)',
        borderColor: 'rgba(59, 130, 246, 1)',
        borderWidth: 1
      }]
    };

    // Chart configuration for appointments chart
    const appointmentsConfig = {
      type: 'bar',
      data: appointmentsData,
      options: {
        responsive: true,
        plugins: {
          legend: { display: true, position: 'top' },
          title: { display: true, text: 'Appointments by Time Slot' }
        },
        scales: {
          y: {
            beginAtZero: true,
            ticks: { stepSize: 1 }
          }
        }
      }
    };

    // Chart configuration for revenue chart
    const revenueConfig = {
      type: 'bar',
      data: revenueData,
      options: {
        responsive: true,
        plugins: {
          legend: { display: true, position: 'top' },
          title: { display: true, text: 'Revenue by Time Slot' }
        },
        scales: {
          y: {
            beginAtZero: true,
            ticks: { stepSize: 50 }
          }
        }
      }
    };

    // Initialize the charts
    const appointmentsCtx = document.getElementById('appointmentsChart').getContext('2d');
    const revenueCtx = document.getElementById('revenueChart').getContext('2d');

    let appointmentsChart = new Chart(appointmentsCtx, appointmentsConfig);
    let revenueChart = new Chart(revenueCtx, revenueConfig);

    // Update the charts on clicking "Get Analytics" (dummy functionality for now)
    document.getElementById('getAnalytics').addEventListener('click', function() {
      // Here you would retrieve updated data based on the selected date.
      // For now, we simply reload the dummy data.
      appointmentsChart.destroy();
      revenueChart.destroy();
      appointmentsChart = new Chart(appointmentsCtx, appointmentsConfig);
      revenueChart = new Chart(revenueCtx, revenueConfig);
    });
  </script>
</body>
</html>
