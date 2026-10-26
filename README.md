# realtime-service

Keeps a WebSocket open to every app that is online and pushes new messages to it as they arrive. It also tracks presence and relays encrypted typing indicators. It stores nothing permanently; presence lives in a NATS key-value bucket that expires on its own.

Built with .NET 10 and NATS. Scales with the number of open connections.

Owner: Amar Mehić. Status: planned.

## Where this fits

This is one of the repositories of [Pretty Good Pigeon](https://github.com/rso-ekipa13), an end-to-end encrypted messenger built by ekipa 13 for the Cloud Computing course at UL FRI (2026/27). The architecture, plan and decisions live in [docs](https://github.com/rso-ekipa13/docs).

`main` only changes through pull requests; day-to-day work goes to `dev`.
