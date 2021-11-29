---
layout: page
title: ShengBTE
description: Solving the Boltzmann Transport Equation for phonons.
img: assets/img/shengbte-flow.png
importance: 1
category: works
bitbucket: https://bitbucket.org/sousaw/shengbte
---

<div class="tyJCtd mGzaTb baZpAe">
    <p class="CDt4Ke zfr3Q" dir="ltr">ShengBTE is a software package for solving the Boltzmann Transport Equation for phonons. Its main purpose is to compute the lattice contribution to the thermal conductivity of bulk crystalline solids, but nanowires can also be treated under a hypothesis of diffusive boundary conditions. In addition to the thermal conductivity itself, ShengBTE computes and outputs plenty of additional information about the system under study. See the
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="/features">
                <strong>Features</strong>
            </a>
        </span>
        page for a more complete description. Our method is fully parameter-free, and within its limits of applicability it can yield excellent agreement with experiment. In contrast with parametric methods, it can also be used to predict the lattice thermal conductivity of uncharacterized or even as-yet-unsynthesized materials.</p>
    <p class="CDt4Ke zfr3Q" dir="ltr">As inputs, ShengBTE needs sets of 2nd- and 3rd-order interatomic force constants, and possibly also values of the dielectric parameters of the solid. This set of variables is typically computed
        <em>ab initio</em>
        using a DFT package such as
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="http://www.google.com/url?q=http%3A%2F%2Fwww.vasp.at&amp;sa=D&amp;sntz=1&amp;usg=AFQjCNHnHThEytK5VRudnWrhR1lkXKDg1A" target="_blank">
                <strong>VASP</strong>
            </a>
        </span>
        or
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="http://www.google.com/url?q=http%3A%2F%2Fwww.quantum-espresso.org&amp;sa=D&amp;sntz=1&amp;usg=AFQjCNHrfJK6KhjZDod03jgxtwdP5orqNA" target="_blank">
                <strong>Quantum Espresso</strong>
            </a>
        </span>. In some occasions these programs can compute 2nd-order constants directly; in others, auxiliary software such as
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="http://www.google.com/url?q=http%3A%2F%2Fphonopy.sourceforge.net&amp;sa=D&amp;sntz=1&amp;usg=AFQjCNHzMNCdNV94aDapkhemUnhUVlku7w" target="_blank">
                <strong>Phonopy</strong>
            </a>
        </span>
        needs to be used to facilitate the process.
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="/contributors">
                <strong>We</strong>
            </a>
        </span>
        have developed our own software, thirdorder.py, to fulfill a similar role in the third-order calculations. This site is also the home of thirdorder.py.</p>
    <p class="CDt4Ke zfr3Q" dir="ltr">Both ShengBTE and thirdorder.py are
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="http://www.google.com/url?q=http%3A%2F%2Fwww.gnu.org%2Fphilosophy%2Ffree-sw.html&amp;sa=D&amp;sntz=1&amp;usg=AFQjCNHjzUYxyTGiVXd2GHhN96xLY1s71w" target="_blank">
                <strong>free sofware</strong>
            </a>
        </span>, licensed under the
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="http://www.google.com/url?q=http%3A%2F%2Fwww.gnu.org%2Flicenses%2Fgpl-3.0-standalone.html&amp;sa=D&amp;sntz=1&amp;usg=AFQjCNHlUjv-o1O-YscK_qPaDKu4od-GAw" target="_blank">
                <strong>GNU General Public License version 3</strong>
            </a>
        </span>
        or later. We encourage contributions to this project. If you are interested, please see the
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="/development">
                <strong>Development</strong>
            </a>
        </span>
        page for details. If you just want to use them, proceed to the
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="/downloads">
                <strong>Downloads</strong>
            </a>
        </span>
        section. Complete usage documentation in included with both packages, but you may find it more convenient to access those files from the
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="/documentation">
                <strong>Documentation</strong>
            </a>
        </span>
        page.</p>
    <p class="CDt4Ke zfr3Q" dir="ltr">If you use ShengBTE and/or thirdorder.py and publish your results, please support our work by
        <span class=" aw5Odc" style="font-family: 'Open Sans'; text-decoration: underline;">
            <a class="XqQF9c" href="/how-to-cite">
                <strong>citing us</strong>
            </a>
        </span>.</p>
</div>
