
<h1> Hi, there! <span style="padding-left: 25px">👋</span></h1> 

https://www.software-engineering-unlocked.com/

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Future-2022/new/blob/main/pngwing.com.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/Future-2022/new/blob/main/pngwing.com.png">
  <img alt="Shows an illustrated sun in light color mode and a moon with stars in dark color mode." src="https://github.com/Future-2022/new/blob/main/pngwing.com.png" width="400px" height="250px" align="right">
</picture>


I am <strong className='text-info'>Senior Blockchain and Web Developer</strong> with Strongest high skills.
I'm a passionate web & blockchain developer who is early adaptive and follows a trend always.
As a Blockchain Developer. I am a firm believer that technology can be used to promote equality, transparency, and freedom.

My expertise lies in developing smart contracts, initial coin offerings (ICO), decentralized applications (Dapps) and token protocols. I am also proficient in Solidity and Ethereum Virtual Machine (EVM).

I'm passionate about blockchain, and I think the technology stands to be at the forefront of many industries. My favorite part of developing is always brainstorming the next big idea and then making it a reality. I'm also happy to help you come up with that next big idea.


My strongest skills are:

     ✔️ React.js, Vue.js, Antular.js, Next.js, Typescript.js and so on (Frontend)
     
     ✔️ PHP/Laravel, Node.js/Express.js, Django, Flask (Backend)
     
     ✔️ Ethereum, Solana, Binance Smart Chain(BSC), Polygon
     
     ✔️ Solidity, Rust, Web3
     
     ✔️ Token ( ERC20... | BEP20... )
     
     ✔️ Smart Contracts ( Solidity | Rust )
     
     ✔️ NFT ( Pre-sale | Mint | Marketplace | Stake )
     
     ✔️ DeFi/DEX ( Forking Olympus Dao | Pancakeswap )
     
     ✔️ Fund Token for trading expert
     
     ✔️ ICO & IDO
     
     ✔️ C/C++
     
     ✔️ Unity 3D, Game development, 3D modeling
     
     ✔️ PHP Frameworks(Laravel, Codeignitor, CakePHP, Yii/Yii2, etc)     
     
     ✔️ MongoDB, MySQL

From requirement analysis, architect design, db modeling to frontend/backend coding and maintenance, I provide 100% reliable service.

    1️⃣ Guarantees Fast progress and best quality Constant report and instant reply Cooperative idea support and polite after service
    
    2️⃣ Availability As many others do

I work full time day and night. 8+ hours a day, 6 days a week.
Looking forward to working with you in a long term.

Kindly Regard!


server_name ***  www.***;

	location / {
		# First attempt to serve request as file, then
		# as directory, then fall back to displaying a 404.
		try_files $uri /index.html;

	}

	location /api {
        	proxy_pass http://localhost:5000/api;
        	proxy_http_version 1.1;
        	proxy_set_header Upgrade $http_upgrade;
        	proxy_set_header Connection 'upgrade';
        	proxy_set_header Host $host;
        	proxy_cache_bypass $http_upgrade;
  }

