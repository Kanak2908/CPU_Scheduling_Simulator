# CPU Scheduling Simulator

An interactive simulator for learning and testing various CPU scheduling algorithms, including First Come First Serve (FCFS), Round Robin(RR), Shortest Job First(SJF) and Shortest Remaining Time First(SRTF). This project provides a visual and dynamic way to understand scheduling algorithms, making it ideal for students and enthusiasts interested in operating systems.

**[View the live application here](https://scheduling-algorithm-simulator.vercel.app/)**.

## Overview

This project is a web-based simulator for CPU scheduling algorithms. It allows users to input different processes with specific attributes (arrival time, burst time, etc.) and visualize how these processes are scheduled according to the chosen scheduling algorithm.

## Features

- **Interactive Form**: Add and configure processes with attributes such as arrival time, burst time, and background color.
- **Scheduling Algorithms**: Currently supports FCFS (First Come First Serve), RR (Round Robin), SJF (Shortest Job First) and SRTF (Shortest Remaining Time First).
- **Real-Time Visualization**: Watch processes as they are scheduled and executed based on selected algorithms.
- **Dark Mode Support**: Uses a ThemeProvider for seamless switching between dark and light themes.

## Technologies Used

- **Next.js**: Frontend framework for React applications.
- **TypeScript**: Provides type safety and ensures code robustness.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Zod**: For form validation schemas.
- **React Hook Form**: Handles form state and validation.
- **Custom Components**: Built-in components like `GradientPicker` for user-friendly UI interactions.
