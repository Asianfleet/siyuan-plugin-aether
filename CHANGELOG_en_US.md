<p align="center">
    <img src="asset/aether-thin.png" alt="catenaconf logo" width=100%/>
</p>

[1.x changelog](CHANGELOG.md)

## v2.1.0
- Added message history export function
- Added user message folding feature: when enabled, user input messages that are too long will be automatically folded, only displaying partial content, and clicking to expand will display the full content
- When dragging a Siyuan tab to the input box, if the notebook is in focus, only the focused part will be extracted as context

## v2.0.1
- Support top_p parameter
- Fixed compatibility issues with kmind plugin

## v2.0.0

Refactor plugin code

- UI style optimization
- Added rules and command features
- Input box
  - Added display of current conversation context consumption
  - Added clipboard for temporary text storage
- Conversation interface
  - Removed old message cards
  - Added conversation directory for quick navigation to specific conversations
  - Added "Back to top" button for quick return to conversation top (also can be used to return to bottom)
  - Added HTML code block preview
  - Added message content selection toolbar for selecting, copying, quoting, and asking about message content
  - Support for moving messages to background generation
- Conversation history
  - Added conversation pinning, renaming, and tagging features
  - Added conversation search function with tag filtering support
  - Background messages support generation termination
- Standalone window mode
  - Major interface layout adjustment
  - Message history directly located on the left side of interface, draggable to adjust width, hide/expand
  - Responsive layout supporting narrow and wide screens

