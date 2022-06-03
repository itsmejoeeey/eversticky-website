---
layout: default
title: "Install"
active: "install"
---

## Download

EverSticky is compatible with most up-to-date Linux systems. It relies primarily on Qt with Qt WebEngine and will run on any desktop environment.
Packages are provided for a number of current Linux distributions.

_EverSticky is now available on the Snap Store._

<br/>

##### Find instructions specific to your distribution below:
<br/>
<div class="row pt-3">
    <div class="col-md-3">
        <ul class="list-unstyled">
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/debian.png" }}" />Debian</li>
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/ubuntu.png" }}" />Ubuntu</li>
            <li class="pb-2"><img width="32" height="32" class="d-inline-block me-2" src="{{ "/assets/img/distros/pop_os.png" }}" />Pop!_OS</li>
        </ul>
    </div>
    <div class="col-md-9">
        <p>Available from the Snap Store.</p>
        <p><a href="https://snapcraft.io/eversticky">
            <img alt="Get it from the Snap Store" src="{{ "/assets/img/snap-store-black.svg" }}" />
        </a></p>
        <p><b>OR</b></p>
        <p>For Ubuntu (and Ubuntu-deriviatives) simply install the deb software package. <i>This package is far smaller in size than the Snap Store version but will not auto-update.</i></p>
        <p>Run the following commands:</p>
        <pre><code>wget https://github.com/itsmejoeeey/eversticky/releases/download/v0.96.0/eversticky_0.96.0-1_amd64.deb
sudo apt install ./eversticky_0.96.0-1_amd64.deb</code></pre>
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
