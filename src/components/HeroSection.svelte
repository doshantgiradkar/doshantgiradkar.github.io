<script>
	import { resolve } from "$app/paths";
</script>
<section id="hero">
    <div class="text">
        <h1>Hi, I am Doshant</h1>
        <p>
            A Full Stack developer skilled in MongoDB, React Js, Express Js &
            Node Js. Experienced in MERN Stack Development, Frontend and
            Backend, RESTful APIs, Database Management and deliver secure &
            high‐performance applications.
        </p>
        <div>
            <a href={resolve("/skills")}>
                <i class="fa-solid fa-code"></i>
                <span>Skills</span>
            </a>
            <a href={resolve("/projects")}>
                <i class="fa-solid fa-code-branch"></i>
                <span>Projects</span>
            </a>
            <a href={resolve("/contact")}>
                <i class="fa-solid fa-envelope"></i>
                <span>Contact</span>
            </a>
        </div>
    </div>
    <div class="pic"></div>
</section>
