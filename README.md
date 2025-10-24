# Genetic Algorithm 0/1 Knapsack Visualizer

Interactive web app that visualizes how Genetic Algorithms solve the 0/1 Knapsack optimization problem in real-time.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61dafb.svg)

**[Live Demo](#https://isaamrat.github.io/knapsack-visualizer/)**

---

## ✨ Features

### 🧬 Complete Genetic Algorithm Implementation
- **Multiple Selection Methods** - Truncation (75%) and Tournament selection with adjustable K
- **Flexible Crossover** - One-point and two-point crossover with configurable rates (0-100%)
- **Smart Mutation** - Bit-flip mutation with adjustable probability per gene
- **Elitism Support** - Preserve top performers across generations
- **Automatic Fitness Evaluation** - Instant penalty for overweight solutions

### 📊 Rich Real-Time Visualizations
- **Population Grid** - Color-coded chromosomes showing fitness levels at a glance
  - Purple/Blue gradient for high fitness
  - Gray for low fitness
  - Red outline for invalid (overweight) solutions
  - Crown icons marking elite chromosomes
- **Live Fitness Chart** - Track best, average, and median fitness evolution over generations
- **Best Solution Panel** - Always displays optimal solution with item breakdown
- **Chromosome Inspector** - Deep-dive into any solution with detailed gene analysis
- **Operation Logs** - Real-time explanations of selection, crossover, and mutation events

### 🎮 Interactive Learning Controls
- **Step-by-Step Mode** - Execute one generation at a time to understand each operation
- **Auto-Run Mode** - Watch evolution happen with adjustable speed (slow to fast)
- **Manual Experimentation** - Click chromosomes to inspect, compare, and learn
- **Live Parameter Tuning** - Change GA settings on the fly and see immediate effects
- **Editable Problem Dataset** - Add, remove, or modify items and capacity anytime

### 🔬 Educational & Research Tools
- **Reproducible Experiments** - Seeded random number generator ensures identical runs
- **Convergence Detection** - Smart stopping on stagnation (20 gens) or optimal solution
- **Stagnation Warnings** - Visual alerts when algorithm isn't improving
- **Parameter Comparison** - Test different settings with same seed for fair analysis
- **What-If Analysis** - Instantly see how mutation/crossover rates affect outcomes

### ⚙️ Full Customization
- **Problem Configuration**
  - Adjustable knapsack capacity
  - Custom items with any weight/value
  - Pre-loaded example with 10 items
  - Add/delete items on the fly
  
- **GA Hyperparameters**
  - Population size (4-100)
  - Selection method (Truncate/Tournament)
  - Crossover rate (0-100%)
  - Crossover type (One-point/Two-point)
  - Mutation rate (0-50%)
  - Elitism count (0-population)
  - Max generations (10-1000)
  - Random seed for reproducibility

### 🎯 Smart Algorithm Features
- **Multiple Convergence Criteria**
  - Maximum generations reached
  - No improvement for 20 generations (stagnation)
  - All valid solutions identical (optimal convergence)
- **Overweight Handling** - Invalid solutions receive fitness = 0
- **Elite Preservation** - Best solutions automatically advance
- **Generation Tracking** - Full history with statistics

---

## 📖 How to Use

### Basic Workflow
1. **Click "Initialize"** → Creates random population of 20 chromosomes
2. **Click "Run"** → Watch automatic evolution OR **"Step"** → Execute one generation at a time
3. **Click any chromosome** → Inspect genes, weight, value, and fitness
4. **Adjust parameters** → Change mutation rate, crossover type, population size
5. **Compare runs** → Use same seed with different parameters to see effects

### Understanding the Interface
- **Left Panel** - Problem setup and GA parameter controls
- **Top Bar** - Run/pause/step controls with speed slider
- **Center** - Population grid and best solution display
- **Bottom** - Fitness trends chart and operation logs
- **Inspector** - Click any chromosome for detailed analysis

---

## 🧮 The 0/1 Knapsack Problem

Given items with weights and values, find the optimal combination that maximizes total value without exceeding weight capacity.

**Default Example:** 10 items, capacity = 15 units  
**Challenge:** 2^10 = 1,024 possible combinations to explore  
**Applications:** Resource allocation, budgeting, cargo loading, portfolio optimization

---

## 🎓 Educational Use Cases

### Classroom Experiments
1. **Parameter Sensitivity** - Run with mutation rates 0.01, 0.05, 0.1, 0.2 and compare
2. **Selection Comparison** - Test Truncation vs Tournament with identical seeds
3. **Crossover Analysis** - Observe one-point vs two-point recombination
4. **Elitism Impact** - Compare runs with elitism = 0, 2, 5, 10

### Research Questions
- How does population size affect convergence speed?
- What's the optimal mutation rate for this problem?
- When does elitism help vs hurt diversity?
- How many generations until stagnation?

---


## 🏗️ Tech Stack

React 18 • Tailwind CSS • Recharts • Lucide React

---


## 📝 License

MIT License - Free to use for educational and commercial purposes.

---

## Repository Info

**About:**
```
🧬 Educational GA visualizer for 0/1 Knapsack with step-by-step mode, live fitness tracking, 
chromosome inspection, and full parameter customization. Perfect for learning evolutionary algorithms!
```

---

**Made for students, educators, and AI enthusiasts** ⭐
