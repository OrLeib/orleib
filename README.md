# Hi, I'm Or 👋

Software engineer working across web and mobile: Next.js, TypeScript, React, Capacitor (iOS and Android), Supabase.

## Open source

- **Capgo capacitor-updater:** fixed an iOS race condition that crashed apps in production by moving all plugin events onto the main thread. Merged, released in v8.52.0. ([#932](https://github.com/Cap-go/capacitor-updater/pull/932))
- **Next.js / Turbopack:** fixed `.d.cts` / `.d.mts` declaration files breaking builds when matched by dynamic worker paths. In review. ([#99439](https://github.com/vercel/next.js/pull/99439))
- **Next.js / Turbopack:** fixed `new Worker()` failing in ESM packages that build paths from `import.meta.url`. In review. ([#99457](https://github.com/vercel/next.js/pull/99457))
- **Capacitor:** made iOS plugin event listeners thread-safe, verified with Thread Sanitizer. In review. ([#8635](https://github.com/ionic-team/capacitor/pull/8635))

## Bug reproductions

- [turbopack-dcts-worker-repro](https://github.com/orleib-lab/turbopack-dcts-worker-repro)
- [turbopack-worker-import-meta-repro](https://github.com/orleib-lab/turbopack-worker-import-meta-repro)
