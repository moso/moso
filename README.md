```typescript
type JAMstack = string[];

export const moso: Awaited<Record<string, string|string[]>> = {
    name: 'Morten Sørensen',
    location: 'Denmark',
    title: 'Web Developer @ TV MIDTVEST',
    stack: ['React', 'Vue', 'Vite', 'Markdown', 'TypeScript'] as JAMstack,
    website: 'https://moso.dev',
};
```
