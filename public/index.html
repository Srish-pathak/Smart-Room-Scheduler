<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
  >

  <title>
    IIT BHU Room Booking
  </title>

  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap"
    rel="stylesheet"
  >

  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
  >

  <style>

    * {

      margin: 0;
      padding: 0;
      box-sizing: border-box;

    }

    body {

      font-family: "Poppins", sans-serif;

      background:
        linear-gradient(
          135deg,
          #0f172a,
          #111827
        );

      color: white;

      padding: 30px;

    }

    .container {

      max-width: 1300px;

      margin: auto;

    }

    .top {

      display: flex;

      justify-content: space-between;

      align-items: center;

      margin-bottom: 30px;

    }

    .title h1 {

      font-size: 40px;

    }

    .title p {

      color: #cbd5e1;

    }

    .btn {

      background:
        linear-gradient(
          135deg,
          #8b5cf6,
          #6366f1
        );

      padding: 15px 22px;

      border-radius: 18px;

      color: white;

      text-decoration: none;

      font-weight: 600;

    }

    .grid {

      display: grid;

      grid-template-columns: 1fr 1fr;

      gap: 25px;

    }

    .card {

      background:
        rgba(255,255,255,0.05);

      border-radius: 30px;

      padding: 30px;

      border:
        1px solid rgba(255,255,255,0.08);

    }

    .card h2 {

      margin-bottom: 20px;

    }

    form {

      display: flex;

      flex-direction: column;

      gap: 18px;

    }

    input,
    select,
    button {

      padding: 16px;

      border: none;

      border-radius: 16px;

      font-size: 15px;

    }

    input,
    select {

      background:
        rgba(255,255,255,0.08);

      color: white;

    }

    button {

      cursor: pointer;

      font-weight: 600;

    }

    .check-btn {

      background: #f59e0b;
      color: white;

    }

    .book-btn {

      background:
        linear-gradient(
          135deg,
          #8b5cf6,
          #6366f1
        );

      color: white;

    }

    .status {

      margin-top: 20px;

      padding: 15px;

      border-radius: 16px;

      text-align: center;

      background:
        rgba(255,255,255,0.08);

    }

    .timeline {

      display: flex;

      flex-direction: column;

      gap: 15px;

    }

    .slot {

      background:
        rgba(255,255,255,0.08);

      padding: 18px;

      border-radius: 18px;

    }

    .slot strong {

      color: #a78bfa;

    }

    @media(max-width: 900px) {

      .grid {

        grid-template-columns: 1fr;

      }

    }

  </style>

</head>

<body>

  <div class="container">

    <div class="top">

      <div class="title">

        <h1>
          IIT BHU Room Scheduler
        </h1>

        <p>
          Smart Meeting & Seminar Booking System
        </p>

      </div>

      <div>

        <a
          href="/auth/google"
          class="btn"
        >

          Connect Google

        </a>

        <a
          href="https://calendar.google.com"
          target="_blank"
          class="btn"
        >

          Open Calendar

        </a>

      </div>

    </div>

    <div class="grid">

      <!-- BOOKING -->

      <div class="card">

        <h2>
          Book A Room
        </h2>

        <form
          action="/book-room"
          method="GET"
        >

          <input
            type="text"
            name="title"
            placeholder="Meeting Title"
            required
          >

          <select name="room">

            <option>
              Seminar Hall
            </option>

            <option>
              Conference Room
            </option>

            <option>
              Lab 101
            </option>

          </select>

          <input
            type="date"
            name="date"
            required
          >

          <input
            type="email"
            name="attendee"
            placeholder="Attendee Email"
          >

          <input
            type="time"
            name="start"
            required
          >

          <input
            type="time"
            name="end"
            required
          >

          <button
            type="button"
            class="check-btn"
            onclick="checkAvailability()"
          >

            Check Availability

          </button>

          <button
            type="submit"
            class="book-btn"
          >

            Book Room

          </button>

        </form>

        <div
          class="status"
          id="status"
        >

          Room status will appear here

        </div>

      </div>

      <!-- LIVE BOOKINGS -->

      <div class="card">

        <h2>
          Live Room Schedule
        </h2>

        <div
          class="timeline"
          id="timeline"
        >

          Loading bookings...

        </div>

      </div>

    </div>

  </div>

  <script>

    async function checkAvailability() {

      const room =
        document.querySelector('[name="room"]').value;

      const date =
        document.querySelector('[name="date"]').value;

      const start =
        document.querySelector('[name="start"]').value;

      const end =
        document.querySelector('[name="end"]').value;

      const response =
        await fetch(

          `/check-availability?room=${room}&date=${date}&start=${start}&end=${end}`

        );

      const result =
        await response.text();

      document.getElementById("status")
        .innerHTML =
        "Room Status : " + result;

    }

    async function loadBookings() {

      const response =
        await fetch("/api/bookings");

      const bookings =
        await response.json();

      const timeline =
        document.getElementById("timeline");

      if (bookings.length === 0) {

        timeline.innerHTML =
          "<p>No bookings yet</p>";

        return;

      }

      timeline.innerHTML = "";

      bookings.forEach((booking) => {

        timeline.innerHTML += `

          <div class="slot">

            <strong>
              ${booking.title}
            </strong>

            <br><br>

            Room :
            ${booking.room}

            <br>

            Date :
            ${booking.date}

            <br>

            Time :
            ${booking.start}
            -
            ${booking.end}

          </div>

        `;

      });

    }

    loadBookings();

  </script>

</body>

</html>
