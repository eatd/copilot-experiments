                                                                                                                                                                                                                                            |
**Warning!**
*The following settings are theoretical and may even be against TOS.*

| Setting ID                                                             | Description                                                                                                                  |
| ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------|
| `github.copilot.advanced.debug.overrideChatMaxTokenNum`                | Overrides the maximum number of tokens allowed for a chat request.                                                           |
| `enableInternalDebugLogging`                                           | Activates an enhanced debugging mode, potentially providing more logging and error reporting.                                |
| `perfEvtsSendAll`                                                      | Related to an experimental completion mode called "use-collector-delta."                                                     |
| `telemetry.telemetryLevel`                                             | Controls the level of telemetry data sent to Microsoft. Values: `all`, `error`, `crash`, `off`.                              |
| `github.copilot.renameSuggestions.triggerAutomatically`                | Controls whether automatic rename suggestions are triggered.                                                                 |
| `github.copilot.advanced.debug.overrideCAPIUrl`                        | Overrides the URL for the Copilot API. Primarily used for debugging and testing.                                             |
| `github.copilot.advanced.debug.overrideChatEngine`                     | Overrides the chat model used by Copilot.                                                                                    |
| `github.copilot.advanced.debug.overrideEmbeddingsModel`                | Overrides the embeddings model used by Copilot.                                                                              |
| `github.copilot.advanced.debug.overrideChatOffTopicModel`              | Overrides the off-topic detection model used by Copilot.                                                                     |
| `github.copilot.advanced.debug.overrideChatOffTopicModelTokenizer`     | Overrides the tokenizer used with the off-topic detection model.                                                             |
| `github.copilot.advanced.debug.overrideChatOffTopicModelThreshold`     | Overrides the threshold used for determining off-topic responses. Higher values might make it more sensitive to off-topic content.|
| `github.copilot.advanced.debug.overrideLogLevels`                      | Overrides logging levels for specific categories.                                                                            |
| `github.copilot.advanced.debug.filterLogCategories`                    | Filters log messages based on category. Only messages from included categories will be logged.                               |
| `github.copilot.advanced.debug.reportFeedback`                         | Enables/disables feedback reporting.                                                                                         |
| `github.copilot.advanced.debug.useNodeFetcher`                         | Forces Copilot to use the Node.js fetcher for network requests.                                                              |
| `github.copilot.advanced.debug.useElectronFetcher`                     | Forces Copilot to use the Electron fetcher for network requests (if available).                                              |
| `github.copilot.advanced.slashCommands`                                | Controls the enablement of slash commands.                                                                                   |
| `github.copilot.advanced.variables`                                    | Controls the enablement of conversation variables (like `#selection`).                                                       |
| `github.copilot.advanced.conversationAdditionalPromptContext`          | Controls how much additional context from the conversation history is included in the prompt. Values: `firstTurn`, `allPreviousTurns`.|
| `github.copilot.advanced.conversationLoggingEnabled`                   | Enables/disables logging of conversation interactions.                                                                       |
| `github.copilot.chat.notebookLogEnabled`                               | Enables/disables logging of notebook interactions.                                                                           |
| `github.copilot.advanced.conversationIntentDetection`                  | Enables/disables intent detection for chat requests.                                                                         |
| `github.copilot.advanced.intentDetectionWithFunctionCalling`           | Enables/disables function calling for intent detection.                                                                      |
| `github.copilot.advanced.promptEval`                                   | Enables/disables an experimental prompt evaluation feature.                                                                  |
| `github.copilot.advanced.promptEval.requestContext`                    | Sets the threshold for requesting context in prompt evaluation.                                                              |
| `github.copilot.advanced.kerberosServicePrincipal`                     | Configures the Kerberos service principal to use for proxy authentication.                                                   |
| `github.copilot.advanced.explain.refer`                                | Determines whether the `/explain` command refers to the workspace.                                                           |
| `github.copilot.advanced.fix.inlineChatEndpoint`                       | Specifies which chat model to use for the `/fix` command in inline chat.                                                     |
| `github.copilot.advanced.fix.useWorkspaceChunksFromSelection`          | Controls whether workspace chunks from the selection are used for the `/fix` command.                                        |
| `github.copilot.advanced.fix.useWorkspaceChunksFromDiagnostics`        | Controls whether workspace chunks related to diagnostics are used for the `/fix` command.                                    |
| `github.copilot.advanced.codeMapper.chatEndpoint`                      | Specifies which chat model to use for the code mapper feature.                                                               |
| `github.copilot.advanced.gpt4TurboExperimentEnabled`                   | Allows opting into an experimental feature using the GPT-4 Turbo model.                                                      |
| `github.copilot.advanced.projectLabels.expanded`                       | Controls whether an experimental feature for expanding project labels is enabled.                                            |
| `github.copilot.advanced.projectLabels.chat`                           | Controls whether an experimental feature for using project labels in the chat is enabled.                                    |
| `github.copilot.advanced.projectLabels.inline`                         | Controls whether an experimental feature for using project labels in inline chat is enabled.                                 |
| `github.copilot.chat.useProjectTemplates`                              | Controls whether Copilot uses project templates when responding to "new" requests.                                           |
| `github.copilot.chat.scopeSelection`                                   | Controls whether Copilot will attempt to expand the selection to include more relevant context when using `/explain`.        |
| `github.copilot.advanced.useMessageNames`                              | Controls whether Copilot assigns names to user and assistant messages in the chat.                                           |
| `github.copilot.advanced.feedback.onChange`                            | Controls whether Copilot generates feedback on code changes automatically when you modify a file.                            |
| `github.copilot.advanced.review.contextMenu`                           | Controls whether the "Review using Copilot" code action is shown in the editor context menu.                                 |
| `github.copilot.advanced.review.scmViewlet`                            | Controls whether the "Review using Copilot" action is shown in the source control view.                                      |
| `github.copilot.advanced.review.intent`                                | Controls whether the `/review` command is enabled by default.                                                                |
| `github.copilot.advanced.notebook.prioritiesExperimentEnabled`         | Controls whether an experimental feature that adjusts the priority of different notebook elements in the prompt is enabled.  |
| `github.copilot.advanced.notebook.packagesExperimentEnabled`           | Controls whether an experimental feature for including information about installed packages in notebook prompts is enabled.  |
| `github.copilot.AppInsightsChannelPlugin.enablePerfMgr`                | Enables the "use-collector-delta" completion mode.                                                                           |
| `github.copilot.AppInsightsChannelPlugin.disableOptimizeObj`           | Disables internal object optimization, potentially affecting performance or memory usage.                                    |
| `github.copilot.AppInsightsChannelPlugin.ignoreMc1Ms0CookieProcessing` | Controls cookie processing.                                                                                                  |
| `github.copilot.advanced.runCommandEnabled`                            | Controls whether automatic command execution is enabled for the `/runCommand` intent.                                        |

**Experiment and Share!**
