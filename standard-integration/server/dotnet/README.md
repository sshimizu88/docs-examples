# Standard Integartion .NET Sample

PayPal Standard Integration sample in .NET

## Running the sample

1. **Add your API credentials to the environment:**

   - **Windows**

     ```powershell
     $env:PAYPAL_CLIENT_ID = "<PAYPAL_CLIENT_ID>"
     $env:PAYPAL_CLIENT_SECRET = "<PAYPAL_CLIENT_SECRET>"
     ```

   - **Unix**

     ```bash
     export PAYPAL_CLIENT_ID="<PAYPAL_CLIENT_ID>"
     export PAYPAL_CLIENT_SECRET="<PAYPAL_CLIENT_SECRET>"
     ```

2. **Build the server**

   ```bash
   dotnet restore
   ```

3. **Run the server**

   ```bash
   dotnet run
   ```

4. Go to [http://localhost:8080/](http://localhost:8080/)