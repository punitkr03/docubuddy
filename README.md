<div>
⚠️ I used all the openai credits in dev so I have to disable the chat in production build and it will show pages exceeded always.<br/>
⚠️ I also disabled stripe as I don't intend to accept real payments but the pricing page will still be visible.<br/>
✅ Uploading files will still work till i hit my free limit XD.<br/>
</div>


# DocuBuddy
DocuBuddy is an intelligent SaaS application designed to streamline information retrieval from documents. This powerful tool leverages advanced natural language processing (NLP) and machine learning algorithms to efficiently answer user queries from a variety of document formats. Whether you're dealing with extensive reports, technical documents, or knowledge repositories, DocQuery simplifies the search and extraction process, saving valuable time and enhancing productivity.

# Tech Stack
- Next.js
- openai
- tRPC
- Database: Neon
- ORM: Prisma
- TypeScript
- React
- Stripe
- Tailwind CSS
- shadcn(UI)

# Local Setup
Step 1.
```
git clone https://github.com/punitkr03/docubuddy.git
```
Step 2.
```
pnpm install
```
Step 3.
```
npx prisma generate
```
Step 4.
```
pnpm dev
```
