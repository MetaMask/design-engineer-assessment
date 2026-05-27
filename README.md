# Interactive Address Book Take-Home Assessment

Address Book is a small React application used to evaluate Design Engineer candidates.

---

## Getting Started

```bash
yarn install
yarn dev
```

The app will be available at `http://localhost:5173`.

This project includes [Tailwind CSS v4](https://tailwindcss.com). You're welcome to use it, replace it, or add another styling approach — whatever you're most comfortable with.

---

## The Task

The current application works as a simple searchable address book.

Your task is to improve the search and filtering experience so that it feels polished, intentional, accessible, and pleasant to use.

We are looking for quality of judgment, not quantity of changes. A focused, well-executed improvement is better than many unfinished ideas.

---

## Expected Time

Please spend **3–4 hours** on this exercise.

---

## What Not to Focus On

Please avoid spending significant time on:

- full CRUD functionality
- maps or external APIs
- authentication or backend work
- large routing changes

You may mention future ideas in your notes, but keep the implementation focused on the core interaction.

---

## Project Overview

```
src/
├── context/
│   └── AddressContext.tsx   # Provides address data via React context
├── data/
│   └── addresses.ts         # Mock address data
├── components/
│   ├── AddressBook.tsx      # Main view — search input and results list
│   ├── AddressList.tsx      # Renders filtered results
│   ├── AddressItem.tsx      # Individual address card
│   └── SearchBar.tsx        # Search input
├── pages/
│   └── AddressItemPage.tsx  # Standalone address detail page
└── App.tsx                  # Routes and context provider
```

---

## Deliverables

Please submit:

1. Your completed code
2. A short write-up in `NOTES.md` covering:
   - what you focused on and why
   - what you changed
   - accessibility considerations
   - any tradeoffs you made
   - what you would improve with more time

---

## Submitting Your Work

Share a link to your GitHub repository when you're done. Make sure it's public, or add the interviewer as a collaborator if you'd prefer it private.

---

## Notes

You may use AI-assisted tools if they are part of your normal workflow.
