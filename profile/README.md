# Submilli

[Website](https://submilli.ai/) · [Documentation](https://submilli.ai/docs/) · [Quickstart](https://submilli.ai/docs/quickstart/)

A TypeScript runtime for code-mode agents, with WebAssembly isolation and runtime-enforced semantic permissions.

You specify which operations an agent may perform, on which resources, and with which arguments. The runtime enforces those permissions.

Submilli rethinks the TypeScript execution environment for agents, from the runtime to the [Packages](https://submilli.ai/docs/packages/) they use. These pieces are built together so Packages can describe their operations and the runtime can check them against your rules.

Packages expose typed APIs and declare the Capabilities available to an agent. [Blueprints](https://submilli.ai/docs/blueprints/) select those Packages and define which Capabilities are granted, with constraints on their use.

Connect your agent through MCP or HTTP.

[Runtime](https://github.com/submilli/submilli-runtime) · [Contribute](https://github.com/submilli/submilli-runtime/blob/main/CONTRIBUTING.md) · [Discord](https://discord.gg/VphpukeGGj)

Questions or feedback? Email [hello@submilli.ai](mailto:hello@submilli.ai).
