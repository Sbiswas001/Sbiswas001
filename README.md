[![MasterHead](https://mir-s3-cdn-cf.behance.net/project_modules/fs/54b6c068097599.5b50bca476b9b.gif)]()

<h1 align="center" id="hello-heading">Hello 🌏, I'm Sayan Biswas</h1>
<h3 align="center" id="developer-heading">An undergrad developer from India</h3>
<img align="right" alt="Coding" width="400" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.giphy.com%2Fmedia%2Fko7twHhomhk8E%2Fgiphy.gif&f=1&nofb=1&ipt=4e6061172a077ee127a7fe423e48cb0f16f8733bbb05ea42c58a80993893a5f7&ipo=images">

<p align="left"> <img src="https://komarev.com/ghpvc/?username=sbiswas001&label=Profile%20views&color=0e75b6&style=flat" alt="sbiswas001" /> </p>

<h3 align="left">About Me:</h3>

<div id="about-me">
</div>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/sbiswas001" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="sbiswas001" height="30" width="40" /></a>
<a href="https://instagram.com/sbiswas001" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="sbiswas001" height="30" width="40" /></a>
<a href="https://www.youtube.com/channel/UC5sgQOYGZXxm9mAo8PwyC3g" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="@snipebuddy" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <!-- Add other tools and languages here --> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=sbiswas001&show_icons=true&locale=en&layout=compact" alt="sbiswas001" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=sbiswas001&show_icons=true&locale=en" alt="sbiswas001" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=sbiswas001&" alt="sbiswas001" /></p>

<script>
  const aboutMeText = "🔭 I’m currently working on [Step Tracker](https://github.com/Sbiswas001/StepTracker)\n\n- 🌱 I’m currently learning **Android App Dev**\n\n- 👯 I’m looking to collaborate on [Numplex](https://github.com/Sbiswas001/Numplex495)\n\n- 🤝 I’m looking for help with [Numplex App](https://github.com/Sbiswas001/NumplexApp)\n\n- 👨‍💻 All of my projects are available at [https://github.com/Sbiswas001](https://github.com/Sbiswas001)\n\n- 📝 I regularly write articles on [https://www.linkedin.com/in/sbiswas001](https://www.linkedin.com/in/sbiswas001)\n\n- 💬 Ask me about **java, kotlin, DSA**\n\n- 📫 How to reach me **sbiswas001.tech@gmail.com**\n\n- 📄 Know about my experiences [https://www.linkedin.com/in/sbiswas001](https://www.linkedin.com/in/sbiswas001)\n\n- ⚡ Fun fact **I like documented code**";
  const aboutMeElement = document.getElementById('about-me');

  function typeAboutMe() {
    let index = 0;
    const typingInterval = setInterval(() => {
      if (index === aboutMeText.length) {
        clearInterval(typingInterval);
        setTimeout(eraseAboutMe, 1000); // Wait for 1 second before erasing
      } else {
        aboutMeElement.innerHTML += aboutMeText.charAt(index);
        index++;
      }
    }, 50); // Typing speed
  }

  function eraseAboutMe() {
    let index = aboutMeText.length;
    const erasingInterval = setInterval(() => {
      if (index === 0) {
        clearInterval(erasingInterval);
      } else {
        aboutMeElement.innerHTML = aboutMeText.substring(0, index);
        index--;
      }
    }, 30); // Erasing speed
  }

  typeAboutMe();
</script>
