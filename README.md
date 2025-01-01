<h1><a href="https://prescripto-lime.vercel.app/">Prescripto</a></h1>
<h1>Doctor Appointment Booking Website Using React</h1>
<p>This guide explains how to create and run a React-based frontend for a Doctor Appointment Booking website with features like listing doctors by specialty.</p>
<h2>Steps to Run the React App:</h2>
<ol>
  <li>
    <b>Install Node.js:</b>
    <p>Ensure you have Node.js installed on your system. Download it from <a href="https://nodejs.org" target="_blank">https://nodejs.org</a>.</p>
  </li>
  <li>
    <b>Set Up a React Project:</b>
    <p>Use <code>create-react-app</code> to set up your React project:</p>
    <pre><code>npx create-react-app doctor-booking</code></pre>
  </li>
  <li>
    <b>Navigate to the Project Directory:</b>
    <pre><code>cd doctor-booking</code></pre>
  </li>
  <li>
    <b>Start the Development Server:</b>
    <pre><code>npm start</code></pre>
    <p>This will open the app in your default web browser at <code>http://localhost:3000</code>.</p>
  </li>
  <li>
    <b>Build the Appointment Booking Website:</b>
    <p>Customize the app by editing files in the <code>src</code> folder. You can create components for:</p>
    <ul>
      <li>Homepage</li>
      <li>Doctor Listing by Specialty</li>
      <li>Doctor Profile and Appointment Slots</li>
      <li>Booking Form</li>
      <li>Confirmation Page</li>
    </ul>
  </li>
  <li>
    <b>Fetch Doctor Data:</b>
    <p>Use mock data or integrate with an API to fetch doctor information, specialties, and availability.</p>
    <pre><code>fetch('https://api.example.com/doctors')
  .then(response => response.json())
  .then(data => console.log(data));</code></pre>
  </li>
  <li>
    <b>Build for Production:</b>
    <p>When your app is ready for deployment, run:</p>
  </li>
</ol>



<br /> <hr/>
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
