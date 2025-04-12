# Tenzies Game App - README

## Overview

Welcome to the **Tenzies Game App**! This application is a fun and interactive game built using React. The goal of the game is to roll dice until all dice have the same value. Players can "hold" dice to prevent them from being rolled again, adding strategy to their attempts to win the game. 

The app features sleek design, intuitive gameplay, and delightful animations (such as confetti when the player wins!). It is designed to provide an engaging gaming experience while showcasing the use of modern React features and best practices.

---

## Features

### Core Features:
- **Rolling Dice**: Players can roll all unheld dice with the click of a button.
- **Holding Dice**: Click on a die to hold it, preventing it from being rerolled.
- **Winning Condition**: Confetti animation displays when all dice are held and have the same value.
- **Accessibility**: Screen reader announcements for game events (such as winning the game).

### Technical Highlights:
- Built with **React Functional Components**.
- Uses **useState**, **useRef**, and **useEffect** hooks for state management and interactivity.
- **CSS Modules** for component-level styling, ensuring scoped styles.
- Integrated **react-confetti** for celebratory animations.
- Dynamically-generated unique identifiers for dice using **nanoid**.
- Fully responsive design for a seamless experience across devices.

---

## Installation Instructions

Follow these steps to set up and run the Tenzies Game App locally:

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd tensies-game
