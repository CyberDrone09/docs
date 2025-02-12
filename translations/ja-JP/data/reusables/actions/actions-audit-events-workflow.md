---
ms.openlocfilehash: a2246d16364e870e7cac404da7f75c636f298435
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/05/2022
ms.locfileid: "147065483"
---
| アクション | 説明
|------------------|-------------------
| `cancel_workflow_run` | ワークフローの実行がキャンセルされたときにトリガーされます。 詳細については、「[ワークフローのキャンセル](/actions/managing-workflow-runs/canceling-a-workflow)」を参照してください。{% ifversion fpt or ghec or ghes > 3.2 or ghae-issue-4963 %}
| `completed_workflow_run` | ワークフローの状態が `completed` に変わったときにトリガーされます。 REST APIを通じてのみ見ることができます。UIやJSON/CSVエクスポートでは見ることができません。 詳細については、「[ワークフローの実行履歴の表示](/actions/managing-workflow-runs/viewing-workflow-run-history)」を参照してください。{% endif %}{% ifversion fpt or ghec or ghes > 3.2 or ghae-issue-4963 %}
| `created_workflow_run` | ワークフローの実行が作成されたときにトリガーされます。 REST APIを通じてのみ見ることができます。UIやJSON/CSVエクスポートでは見ることができません。 詳細については、「[ワークフローの例を作成する](/actions/learn-github-actions/introduction-to-github-actions#create-an-example-workflow)」を参照してください。{% endif %}
| `delete_workflow_run` | ワークフローの実行が削除されたときにトリガーされます。 詳細については、「[ワークフロー実行の削除](/actions/managing-workflow-runs/deleting-a-workflow-run)」を参照してください。
| `disable_workflow` | ワークフローが無効化されたときにトリガーされます。
| `enable_workflow` | 以前に `disable_workflow` によって無効にされたワークフローが有効にされたときにトリガーされます。
| `rerun_workflow_run` | ワークフローの実行が再実行されたときにトリガーされます。 詳細については、「[ワークフローの再実行](/actions/managing-workflow-runs/re-running-a-workflow)」を参照してください。{% ifversion fpt or ghec or ghes > 3.2 or ghae-issue-4963 %}
| `prepared_workflow_job` | ワークフロージョブが開始されたときにトリガーされます。 ジョブに渡されたシークレットのリストを含みます。 REST API を使ってのみ表示できます。 これは、{% data variables.product.prodname_dotcom %} Web インターフェイスでは表示されず、JSON/CSV エクスポートにも含まれません。 詳細については、「[ワークフローをトリガーするイベント](/actions/reference/events-that-trigger-workflows)」を参照してください。{% endif %}
| `approve_workflow_job` | ワークフロー ジョブが承認されたときにトリガーされます。 詳細については、「[デプロイの確認](/actions/managing-workflow-runs/reviewing-deployments)」を参照してください。
| `reject_workflow_job` | ワークフロー ジョブが拒否されたときにトリガーされます。 詳細については、「[デプロイの確認](/actions/managing-workflow-runs/reviewing-deployments)」を参照してください。
