---
title: "TikZ"
permalink: /tikz/
author_profile: true
redirect_from:
  - /tikz/
  - /notes/
published: true
layout: archive
---

Here is the Penrose diagram for the maximal analytic extension of the Schwarzschild metric.

<script type="text/tikz">
  \usetikzlibrary{decorations.pathmorphing,patterns}
  \newcommand{\scri}{\mathscr{I}}
  \begin{tikzpicture}
    % Define coordinates for the Penrose diagram
    \coordinate (O) at (0,0); % Origin
    \coordinate (A) at (-4,4); % Top left (i^+)
    \coordinate (B) at (4,4);  % Top right (i^+)
    \coordinate (C) at (4,-4); % Bottom right (i^-)
    \coordinate (D) at (-4,-4); % Bottom left (i^-)
    
    % Draw the diamond shape (conformal boundaries)
    \draw[thick] (A) -- (B) -- (C) -- (D) -- cycle;
    
    % Draw singularity lines
    \draw[thick, decorate, decoration={zigzag, segment length=4, amplitude=2}] (O) -- (A);
    \draw[thick, decorate, decoration={zigzag, segment length=4, amplitude=2}] (O) -- (C);
    
    % Label the regions (simplified)
    \node at (0,2) {I}; % Exterior region
    \node at (-2,0) {II}; % Black hole interior
    \node at (2,0) {III}; % Parallel exterior
    \node at (0,-2) {IV}; % White hole interior
    
    % Label the conformal boundaries
    \node[above] at (0,4) {$\scri^+$};
    \node[below] at (0,-4) {$\scri^-$};
    \node[left] at (-4,0) {$i^-$};
    \node[right] at (4,0) {$i^+$};
    \node[above] at (-2,4) {$i^0$};
    \node[above] at (2,4) {$i^0$};
  \end{tikzpicture}
</script>