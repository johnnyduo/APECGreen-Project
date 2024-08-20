# APEC.green Project

URL: https://apec-green.vercel.app

APEC.Green is an AI-powered trade platform designed to simplify access to international markets for micro, small, and medium enterprises (MSMEs), as well as underserved groups, including women, minorities, and Indigenous Peoples. The platform focuses on promoting sustainable trade practices by integrating advanced AI sustainability filters and providing comprehensive trade credit insurance options. By leveraging the latest Upstage AI technology, APEC.Green delivers a streamlined, transparent, and trustworthy ecosystem for global trade, enabling businesses to succeed while reducing their environmental impact.

## Upstage Usage

### Chat

On the "Export AI Assistant" tab, you can enter your export information to ask the Upstage Export AI Assistant to explore strategies related to carbon footprint, carbon reduction, beneficial policies, and resisting policies. Afterward, you can proceed to complete KYB and purchase trade credit insurance.

![image](https://github.com/user-attachments/assets/8b479234-d9b5-44b8-83cb-eaae1fd9385d)

![image](https://github.com/user-attachments/assets/a5907d36-857c-433f-a872-d9dd23c83313)

### Translation

If you need to translate to Korean, especially for communication with a Korean company, you can press the "Translate to Korean" button to translate the entire response into Korean with one click using Upstage AI.

![image](https://github.com/user-attachments/assets/462e54ad-11e8-461a-80a2-e65dc24a043f)

## Installation and Deployment

To install, follow these steps:

```bash
git clone https://github.com/johnnyduo/APECGreen-Project
cd APECGreen-Project
yarn install
```

Next, set your Upstage token in the `.env` file:

```
VITE_UPSTAGE_TOKEN=up_aI0jwPU2k...
```

To start the development server, run:

```bash
yarn dev
```

If you want to build for production, use the following command:

```bash
yarn build
```

Your built APEC Green website will be located in the `dist` folder, ready to be deployed to your server or using deployment services such as [Vercel](https://vercel.com) or [Cloudflare Pages](https://www.cloudflare.com).
