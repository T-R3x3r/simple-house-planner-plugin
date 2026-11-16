# Simple House Planner

Design houses, apartments, offices and gardens with your assistant. Simple House Planner draws floor plans to scale, floor by floor, with walls, doors, windows, stairs, roofs, furniture, the garden and the site, and shows them in 2D and 3D. The planner checks each step for what you would notice walking through it, such as furniture in the way through a door, and the assistant fixes it.

Your plans are stored in your Simple House Planner account. Open them at [simplehouseplanner.com](https://simplehouseplanner.com/) to change them by hand, and export them as PNG, SVG, PDF sheets to scale, DXF, DWG and IFC.

## Try asking

- Design a two-floor family house with three bedrooms and a gable roof, in Freiburg.
- Add a 4 by 6 meter garage to the east side of my lake house.
- Furnish the living room, and leave room to walk through.
- Turn this sketch into a floor plan. The house is 12 meters wide.
- Check my plan for rooms that do not work.
- How many stairs do I need for a 2.8 meter floor height?
- How much paint do I need for a 4 by 5 meter room?

## Install

In Claude Code:

```
/plugin install simple-house-planner --marketplace T-R3x3r/simple-house-planner-plugin
```

In the Claude apps and ChatGPT, add Simple House Planner from the connector or plugin directory, or add `https://simplehouseplanner.com/mcp` as a custom connector.

## What the plugin contains

- **A connector** to the Simple House Planner MCP server at `https://simplehouseplanner.com/mcp`. Its tools create, change, describe, rename and delete plans in your account, search the furniture catalog, and open the plan in an editor in the chat. Building calculators answer questions about stairs, square footage, flooring, paint, concrete, decks, fences, roofs and more.
- **Skills** that guide the assistant through common tasks: `setup`, `design-house`, `furnish-room`, `plan-from-sketch` and `review-plan`.

The plugin has no hooks, commands, agents or local programs, and it runs nothing on your computer.

## Sign-in and your data

The calculators and the furniture catalog work without an account. Your plans need a free account: the first time a tool needs it, you sign in at simplehouseplanner.com with Google, an email link or a passkey, and signing in the first time creates the account. You can disconnect the assistant from your account settings at any time.

The server receives what the assistant sends to its tools, such as plan titles and the short scripts that change a plan, and it stores your plans in your account. The editor in the chat loads from simplehouseplanner.com and connects only to it. The plugin sends nothing to any other service. The [privacy policy](https://simplehouseplanner.com/privacy/) says what is stored, for how long, and how to delete it.

## Support

Write to support@simplehouseplanner.com or use the [contact page](https://simplehouseplanner.com/contact/).

Plans are design aids. They do not replace the work of an architect or a check against local building rules.
