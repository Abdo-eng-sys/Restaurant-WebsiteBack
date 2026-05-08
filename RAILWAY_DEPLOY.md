# Railway Deployment Notes

## Environment Variables Required
Add these variables in Railway:

APP_NAME=Laravel
APP_ENV=production
APP_DEBUG=false
APP_KEY=base64:GENERATE_THIS_USING_ARTISAN_KEY_GENERATE
APP_URL=https://your-railway-domain.up.railway.app

LOG_CHANNEL=stack
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=YOUR_DB_HOST
DB_PORT=3306
DB_DATABASE=YOUR_DB_NAME
DB_USERNAME=YOUR_DB_USER
DB_PASSWORD=YOUR_DB_PASSWORD

CACHE_DRIVER=file
SESSION_DRIVER=file
QUEUE_CONNECTION=sync

## Deploy
1. Upload this zip to GitHub or Railway.
2. Railway will automatically detect PHP/Laravel.
3. Add the environment variables above.
4. Redeploy the project.
