# How to Generate .fba File for Fitbit Gallery Submission

## Steps

1. **Navigate to your project directory:**
   ```bash
   cd my-first-clock
   ```

2. **Build the project:**
   ```bash
   npx fitbit-build
   ```
   
   This will compile your watchface and generate the `.fba` file.

3. **Locate the .fba file:**
   The `.fba` file will be created in the `build/` directory:
   ```
   build/app.fba
   ```

4. **Upload to Fitbit Gallery:**
   - Go to Fitbit Gallery App Manager
   - Upload the `build/app.fba` file when submitting your watchface

## Notes

- The `.fba` file is a compiled bundle containing your watchface
- Make sure your project builds without errors before generating the .fba
- The file name will be `app.fba` by default
- You can rename it if needed (e.g., `vital-watchface.fba`) before uploading

## Troubleshooting

If the build fails:
- Check for any errors in the build output
- Ensure all dependencies are installed: `npm install`
- Verify your `package.json` configuration is correct
- Check that all required files exist (app/index.js, resources/index.gui, etc.)

