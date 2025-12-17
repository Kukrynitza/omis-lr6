
В frontend\omis-lab-6 добавить файл .env с сдедующием содержанием
NEXT_PUBLIC_SUPABASE_URL=https://toijbtqzpyjjjnutpmin.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=sb_publishable_j9KB7zpR5kYhGvH6rjUtHA_OoaaR6Oe

В backend/main в client = Groq("api_key=GROQ_API_KEY") вместо GROQ_API_KEY вставить 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


backend запускается из папки командой uvicorn main:app --reload --port 8000

Перед запуском необходимо использовать команду из папки frontend\omis-lab-6 npm install для установки всех необходимых библиотек и связей, в дальшейшем frontend запускается из папки frontend\omis-lab-6 командой npm run dev
