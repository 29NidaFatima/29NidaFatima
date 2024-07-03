import React from 'react';
import './App.css';
import LinkedInIcon from './icons/linkedin.svg';
import cIcon from './icons/c.svg';
import css3Icon from './icons/css3.svg';
import html5Icon from './icons/html5.svg';
import javaIcon from './icons/java.svg';
import jsIcon from './icons/javascript.svg';
import mssqlIcon from './icons/mssql.svg';
import mysqlIcon from './icons/mysql.svg';
import reactIcon from './icons/react.svg';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <h1>Hi 👋, I'm Nida Fatima</h1>
        <h3>I am a coding enthusiast</h3>
        <img
          src="https://as1.ftcdn.net/v2/jpg/05/93/82/76/1000_F_593827677_uXCPMbS2ztblOlGRIqSklgjElMKFbNuD.jpg"
          alt="CODING"
          width="250"
          className="coding-image"
        />
        <p>
          📫 How to reach me: <a href="mailto:2529nida17@gmail.com">2529nida17@gmail.com</a>
        </p>

        <h3>Connect with me:</h3>
        <a href="https://www.linkedin.com/in/nida-fatima-005649220?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank" rel="noopener noreferrer">
          <img src={LinkedInIcon} alt="nidafatima" height="30" width="40" />
        </a>

        <h3>Languages and Tools:</h3>
        <div className="icons">
          <img src={cIcon} alt="c" width="40" height="40" />
          <img src={css3Icon} alt="css3" width="40" height="40" />
          <img src={html5Icon} alt="html5" width="40" height="40" />
          <img src={javaIcon} alt="java" width="40" height="40" />
          <img src={jsIcon} alt="javascript" width="40" height="40" />
          <img src={mssqlIcon} alt="mssql" width="40" height="40" />
          <img src={mysqlIcon} alt="mysql" width="40" height="40" />
          <img src={reactIcon} alt="react" width="40" height="40" />
        </div>

        <div className="stats">
          <img
            src={`https://github-readme-stats.vercel.app/api/top-langs?username=29nidafatima&show_icons=true&locale=en&layout=compact`}
            alt="29nidafatima"
          />
          <img
            src={`https://github-readme-stats.vercel.app/api?username=29nidafatima&show_icons=true&locale=en`}
            alt="29nidafatima"
          />
          <img
            src={`https://github-readme-streak-stats.herokuapp.com/?user=29nidafatima`}
            alt="29nidafatima"
          />
        </div>
      </header>
    </div>
  );
}

export default App;
