<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/LeonardoMagalhaes/AdvancedForms">
    <img src="https://www.pngfind.com/pngs/m/530-5309946_to-google-forms-google-forms-logo-png-transparent.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Advanced Forms</h3>

  <p align="center">
    Small project to practice advanced forms using Vite, Zod and Supabase
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Pre-requisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]]<!-- (https://example.com) -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![React][React.js]][React-url]
* [![Vite][ViteJS]][Vite-url]
* [![Supabase][SupabaseJS]][Supabase-url]
* [![Tailwind][TailwindCSS]][Tailwind-url]
* [![Typescript][TypescriptJS]][Typescript-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Please, make sure you have `node` installed on your machine.

### Prerequisites

Run the npm install:
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/LeonardoMagalhaes/AdvancedForms.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Create an account at [https://supabase.com](https://supabase.com)
5. Create a new project in Supabase
6. Go to Storage and create a new bucket
7. Go to Project Settings -> API, and copy the Project URL and Project API Keys/secret
8. Create a new file called `.env based` on the `.env.sample`
9. Replace the values previously copied at your Supabase project settings in the `.env` file.
   ```js
    VITE_SUPABASE_PROJECT_URL={SUPABASE_PROJECT_URL}
    VITE_SUPABASE_API_KEY_SECRET={VITE_SUPABASE_API_KEY_SECRET}
   ```
10. Run
   ```sh
   npm run dev
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This is a POC to put in practice new functionalities and studies.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/LeonardoMagalhaes/AdvancedForms](https://github.com/LeonardoMagalhaes/AdvancedForms)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[contributors-shield]: https://img.shields.io/github/contributors/LeonardoMagalhaes/AdvancedForms.svg?style=for-the-badge
[contributors-url]: https://github.com/LeonardoMagalhaes/AdvancedForms/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/LeonardoMagalhaes/AdvancedForms.svg?style=for-the-badge
[forks-url]: https://github.com/LeonardoMagalhaes/AdvancedForms/network/members
[stars-shield]: https://img.shields.io/github/stars/LeonardoMagalhaes/AdvancedForms.svg?style=for-the-badge
[stars-url]: https://github.com/LeonardoMagalhaes/AdvancedForms/stargazers
[issues-shield]: https://img.shields.io/github/issues/LeonardoMagalhaes/AdvancedForms.svg?style=for-the-badge
[issues-url]: https://github.com/LeonardoMagalhaes/AdvancedForms/issues
[license-shield]: https://img.shields.io/github/license/LeonardoMagalhaes/AdvancedForms.svg?style=for-the-badge
[license-url]: https://github.com/LeonardoMagalhaes/AdvancedForms/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/leonardo-magalhães-alves-b6511153
[product-screenshot]: ./public/projectScreenshot.png
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[ViteJS]: https://img.shields.io/badge/vitejs-646CFF?style=for-the-badge&logo=vite&logoColor=white
[Vite-url]: https://vitejs.dev/
[SupabaseJS]: https://img.shields.io/badge/supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white
[Supabase-url]: https://supabase.com
[TailwindCSS]: https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white
[Tailwind-url]: https://tailwindcss.com
[TypescriptJS]: https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[Typescript-url]: https://www.typescriptlang.org