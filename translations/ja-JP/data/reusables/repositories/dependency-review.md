---
ms.openlocfilehash: c1e28a929a201082b49e4b2327e53c5ddb352769
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/05/2022
ms.locfileid: "147060980"
---
さらに、{% data variables.product.prodname_dotcom %} は、リポジトリの既定のブランチに対して行われた pull request で追加、更新、削除される依存関係を確認し、プロジェクトのセキュリティを低下させる変更にフラグを立てることができます。 これにより、コードベースまで達した後ではなくその前に、脆弱な依存関係{% ifversion GH-advisory-db-supports-malware %}またはマルウェア{% endif %}を見つけて対処できます。 詳細については、「[プル リクエスト内の依存関係の変更をレビューする](/github/collaborating-with-issues-and-pull-requests/reviewing-dependency-changes-in-a-pull-request)」を参照してください。
