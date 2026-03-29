import React from "react";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800 p-6">
      <div className="max-w-5xl mx-auto">
        <header className="mb-10">
          <h1 className="text-4xl font-bold">Vishnu Nair</h1>
          <p className="text-lg mt-2">Associate Consultant | Mainframe Modernization Expert</p>
          <p className="mt-2">Bracknell, UK | vishnunair.nair6@gmail.com</p>
        </header>

        <section className="mb-10">
          <h2 className="text-2xl font-semibold mb-3">Professional Summary</h2>
          <p>
            Associate Consultant with 9+ years of experience in Mainframe development,
            modernization, and client-facing delivery. Specialized in converting legacy
            systems to modern solutions, improving performance, and leading distributed teams.
          </p>
        </section>

        <section className="mb-10">
          <h2 className="text-2xl font-semibold mb-3">Skills</h2>
          <ul className="grid grid-cols-2 gap-2 list-disc list-inside">
            <li>C Programming</li>
            <li>COBOL & Assembler</li>
            <li>IBM Z/OS, DB2, IMS</li>
            <li>Mainframe Modernization</li>
            <li>Agile Delivery</li>
            <li>HTML & CSS</li>
            <li>Leadership & Communication</li>
            <li>Client Interaction</li>
          </ul>
        </section>

        <section className="mb-10">
          <h2 className="text-2xl font-semibold mb-3">Experience</h2>
          <div className="mb-6">
            <h3 className="font-bold">Assistant Consultant - TCS (2024 - Present)</h3>
            <p>
              Leading modernization initiatives by converting legacy ASM modules to C,
              improving system performance and maintainability.
            </p>
          </div>
          <div className="mb-6">
            <h3 className="font-bold">Onsite Coordinator (2022 - 2024)</h3>
            <p>
              Acted as bridge between client and offshore teams, ensuring smooth delivery
              and communication.
            </p>
          </div>
          <div>
            <h3 className="font-bold">Offshore Lead & Developer (2015 - 2022)</h3>
            <p>
              Designed scalable solutions, delivered defect-free code, and led development teams.
            </p>
          </div>
        </section>

        <section className="mb-10">
          <h2 className="text-2xl font-semibold mb-3">Projects</h2>
          <ul className="list-disc list-inside">
            <li>
              Mainframe Modernization (ASM to C Conversion) – Improved maintainability
              and reduced operational risk.
            </li>
            <li>
              Robot Navigation using Optical Odometry – Solved odometer inaccuracies
              using optical sensors.
            </li>
          </ul>
        </section>

        <section className="mb-10">
          <h2 className="text-2xl font-semibold mb-3">Education</h
