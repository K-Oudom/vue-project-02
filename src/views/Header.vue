<template>
    <div>
        <ul>
            <li>
                <router-link :to="{name:'home'}" class="active" id="home"><i class="bi bi-house navicon"></i>Home</router-link>
            </li>
            <li>
                <router-link :to="{name:'about'}" id="about"><i class="bi bi-person navicon"></i>About</router-link>
            </li>
            <li>
                <router-link :to="{name:'resume'}" id="resume"><i class="bi bi-file-earmark-text navicon"></i>Resume</router-link>
            </li>
            <li>
                <router-link :to="{name:'skill'}" id="skill"><i class="bi bi-briefcase navicon"></i>Skill</router-link>
            </li>
            <li>
                <router-link :to="{name:'contact'}" id="contact"><i class="bi bi-envelope navicon"></i>Contact</router-link>
            </li>
      </ul>
    </div>
</template>