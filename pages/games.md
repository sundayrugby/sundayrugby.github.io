---
layout: page
title: Games
permalink: /games
---

<div class="games-grid">
  <a href="{{ site.github.url }}/rugby-runner" class="game-card">
    <div class="game-card-icon">🏉</div>
    <div class="game-card-title">Rugby Runner</div>
    <div class="game-card-desc">Jump over tacklers — how far can you run?</div>
  </a>
  <a href="{{ site.github.url }}/game" class="game-card">
    <div class="game-card-icon">🏃</div>
    <div class="game-card-title">Side Stepper</div>
    <div class="game-card-desc">Dodge the rocks — how long can you last?</div>
  </a>
</div>

<style>
.games-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 20px;
}
.game-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 160px;
  height: 160px;
  border: 2px solid black;
  border-radius: 8px;
  text-align: center;
  padding: 16px;
  text-decoration: none;
  color: black;
  transition: background 0.2s;
}
.game-card:hover {
  background: #f5f5f5;
}
.game-card-icon {
  font-size: 2.5rem;
  margin-bottom: 8px;
}
.game-card-title {
  font-weight: bold;
  margin-bottom: 6px;
}
.game-card-desc {
  font-size: 0.75rem;
  color: #555;
}
</style>
