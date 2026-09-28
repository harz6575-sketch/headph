# inPods 12 TWS landing

Лендінг з вузьким центральним макетом у стилі односторінкових товарних сторінок: великий перший банер, ціна, форма, блоки переваг, характеристики, фото, відгуки та повторна форма.

## Функції
- 2 форми замовлення: верхня і нижня;
- `/api/order` для передачі заявки;
- Telegram, LP-CRM і HubSpot у серверному endpoint;
- UTM-параметри: `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`;
- Meta Pixel `Lead` після успішної заявки;
- Google Analytics;
- таймер до 23:59:59 поточного дня;
- плавний скрол до нижньої форми;
- lightbox для фото;
- sticky CTA-кнопка;
- адаптивність під мобільні екрани;
- використані надані фото 01, 02, 04–11; фото 03 навмисно не включене.

## Vercel env
`TELEGRAM_BOT_TOKEN`  
`TELEGRAM_CHAT_ID`  
`LPCRM_API_KEY`  
`LPCRM_PRODUCT_ID`  
`LPCRM_SITE_URL`  
`HUBSPOT_ACCESS_TOKEN`

Перед деплоєм перевірте, що `LPCRM_PRODUCT_ID` відповідає саме товару inPods 12, а `LPCRM_SITE_URL` містить URL цього лендингу.
