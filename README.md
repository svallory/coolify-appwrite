# Appwrite 1.7.4 on Coolify 4.0.0 beta 418

## Instructions

1. Download the `appwrite.env` and edit with your options (domain, keys, etc)

  > [!IMPORTANT]
  > - DO NOT set a password for Redis unless you are connecting to an external one
  > - Keep the `*_FORCE_HTTPS` variables `disabled` or it will not work.<br>
  >   Don't worry, Coolify will handle https.

2. Go to Coolify and create a new resource selecting "Docker Compose Empty"
  <img width="668" alt="image" src="https://gist.github.com/user-attachments/assets/4aafbc23-9769-4d9f-865d-69140ffb8d78" />
 
3. Paste the `docker-compose.yml` file from this gist

4. Go straight to `Environment Variables` and paste the code of the `appwrite.env` you edited

5. Configure the URLs and disable the "Strip Prefixes" option for the containers below

   - Appwrite -> `https://<your-domain>`
   - Appwrite Console -> `https://<your-domain>/console`
   - Appwrite Realtime -> `https://<your-domain>/v1/realtime`

<img width="468" alt="image" src="https://gist.github.com/user-attachments/assets/56de82ca-37c1-4e04-a42c-be5e16e4add7" />
