---
layout: default
title: "Install"
active: "install"
---

## Download

EverSticky is compatible with most up-to-date Linux systems. It relies primarily on Qt with Qt WebEngine and will run on any desktop environment. Packages are provided for a number of current Linux distributions.

Find instructions specific to your distribution below:

<div class="row pt-3">
    <div class="col-md-3">
        <ul class="list-unstyled">
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/debian.png" }}" />Debian</li>
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/ubuntu.png" }}" />Ubuntu</li>
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/pop_os.png" }}" />Pop!_OS</li>
        </ul>
    </div>
    <div class="col-md-9">
        <p>For Ubuntu (and Ubuntu-deriviatives) simply install the deb software package.</p>
        <pre><code>wget https://github.com/itsmejoeeey/eversticky/releases/download/v0.95.0/eversticky_0.95.0-1_amd64.deb
sudo apt install ./eversticky_0.95.0-1_amd64.deb</code></pre>
        <p>Snap coming soon...</p>
    </div>
</div>

<hr class="my-3 mx-auto">

<div class="row pt-3 pb-4">
    <div class="col-md-3">
        <ul class="list-unstyled">
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/arch.png" }}" />Arch Linux</li>
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/manjaro.png" }}" />Manjaro</li>
        </ul>
    </div>
    <div class="col-md-9 styled-links">
        <p>Available in the <a href="https://aur.archlinux.org/packages/eversticky/">Arch User Repository</a>.</p>
    </div>
</div>

## Compile from source

> **⚠ IMPORTANT NOTE:**  
> You will need a production Evernote API key to compile the application and be able to see and alter notes you currently store on Evernote. This secret (along with the desired domain and key) needs to be provided at the top of ./src/eversticky.pro.

<p class="styled-links">
    See the compilation instructions in the project <a href="https://github.com/itsmejoeeey/eversticky#compiling-from-source">README on Github</a>.
</p>
