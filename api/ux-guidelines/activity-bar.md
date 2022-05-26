# Activity Bar

The Activity Bar is a core navigation surface in VS Code. Extensions can contribute items to the Activity Bar that open [View Containers](api/ux-guidelines/views#view-containers) in the Primary Sidebar.

**✔️ Do**

- Use an icon that matches the default Activity Bar item icon style
- Use a clear, obvious name for the View Container associated with the item

**❌ Don't**

- Duplicate an existing icon
- Use an Activity Bar item to open a Webview Panel

![Example of the Activity Bar](images/examples/activity-bar.png)

## Related Resources
- [View Container API Reference](https://code.visualstudio.com/api/references/contribution-points#contributes.viewsContainers)
- [View API Reference](https://code.visualstudio.com/api/references/contribution-points#contributes.views)
- [Product Icon Reference](https://code.visualstudio.com/api/references/icons-in-labels)
