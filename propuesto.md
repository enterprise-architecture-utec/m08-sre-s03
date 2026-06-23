# Ejercicio propuesto:

1. Ir al repositorio https://github.com/aws-samples/serverless-observability-workshop/tree/master y levantar codespace.
   <img width="611" height="406" alt="image" src="https://github.com/user-attachments/assets/77dd95fc-3ba3-4b7d-958e-154f7049e117" />

2. En codespace instalar AWS CLI y SAM:
   ```
   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   unzip awscliv2.zip
   sudo ./aws/install
   ```

   ```
   wget https://github.com/aws/aws-sam-cli/releases/latest/download/aws-sam-cli-linux-x86_64.zip
   unzip aws-sam-cli-linux-x86_64.zip -d sam-installation
   sudo ./sam-installation/install
   ```

3. Configurar credenciales:
   export AWS_DEFAULT_REGION=us-east-1
   export AWS_ACCESS_KEY_ID="XXXX"
   export AWS_SECRET_ACCESS_KEY="XXXXX"
   export AWS_SESSION_TOKEN="XXXXX"

4. Continuar laboratorio en https://catalog.us-east-1.prod.workshops.aws/workshops/b3fc5f7a-ff34-41fa-a9f2-4cd9e093e6ff/en-US
   
