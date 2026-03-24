---
title: "Organizing Committees"
url: "/committees/"
custom_layout: true
---

<style>
.committee-group { margin-bottom: 4rem; }
.committee-group h2 { margin-bottom: 2rem; padding-bottom: 0.5rem; border-bottom: 2px solid #e2e8f0; color: var(--clr-primary); }
.member-list { display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 1.5rem; }
.member-card { background: white; padding: 1.5rem; border-radius: 8px; box-shadow: var(--shadow-sm); display: flex; align-items: center; gap: 1.5rem; transition: transform var(--transition-fast), box-shadow var(--transition-fast); }
.member-card:hover { transform: translateY(-3px); box-shadow: var(--shadow-md); }
.member-avatar { width: 70px; height: 70px; border-radius: 50%; background-color: var(--bg-light); display: flex; align-items: center; justify-content: center; font-size: 1.5rem; color: var(--clr-secondary); flex-shrink: 0; overflow: hidden; }
.member-avatar img { width: 100%; height: 100%; object-fit: cover; }
.member-info h4 { margin-bottom: 0.25rem; font-size: 1.1rem; }
.member-role { font-size: 0.85rem; color: var(--clr-accent); font-weight: 600; margin-bottom: 0.15rem; text-transform: uppercase; }
.member-inst { font-size: 0.9rem; color: var(--text-muted); }
</style>

<div class="committee-group fade-up">
<h2>Local Organizing Committee (LOC)</h2>

<div class="member-list">
{{< member name="Dr. Jane Doe" role="Chair" inst="National Laboratory, Country" >}}
{{< member name="Prof. John Smith" role="Co-Chair" inst="University of Science, Country" >}}
{{< member name="Dr. Alan Turing" role="Scientific Program" inst="Institute of Physics, Country" >}}
{{< member name="Sarah Connor" role="Logistics" inst="Event Horizon Corp, Country" >}}
</div>
</div>

<div class="committee-group fade-up delay-1">
<h2>Scientific Advisory Board (SAB)</h2>

<div class="member-list">
{{< member name="Dr. Albert Einstein" inst="Advanced Studies Inst, Country" icon="user-graduate" >}}
{{< member name="Dr. Marie Curie" inst="Radiological Labs, Country" icon="user-graduate" >}}
{{< member name="Prof. Niels Bohr" inst="Quantum Mechanics Univ, Country" icon="user-graduate" >}}
{{< member name="Dr. Enrico Fermi" inst="Reactor Facilities, Country" icon="user-graduate" >}}
{{< member name="Dr. Lise Meitner" inst="Fission Research, Country" icon="user-graduate" >}}
{{< member name="Prof. Richard Feynman" inst="QED Institute, Country" icon="user-graduate" >}}
</div>
</div>
