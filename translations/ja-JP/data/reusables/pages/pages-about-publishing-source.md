---
ms.openlocfilehash: f77827f645123477cf9ddc2f845c7da3a4929a72
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/05/2022
ms.locfileid: "147428433"
---
{% ifversion pages-custom-workflow %}

変更が特定のブランチにプッシュされたときにサイトを公開できます。または、{% data variables.product.prodname_actions %} ワークフローを記述してサイトを公開することもできます。

サイトのビルド プロセスを制御する必要がない場合は、変更が特定のブランチにプッシュされたときにサイトを公開することをお勧めします。 {% data reusables.pages.pages-about-branch-source %}

Jekyll 以外のビルド プロセスを使用する場合、または専用ブランチでコンパイル済みの静的ファイルを保持したくない場合は、{% data variables.product.prodname_actions %} ワークフローを記述してサイトを公開することをお勧めします。 {% data variables.product.product_name %} には、ワークフローの記述に役立つ一般的な公開シナリオ用のスターター ワークフローが用意されています。

{% else %}

{% data variables.product.prodname_pages %} サイトは、変更が特定のブランチにプッシュされるたびに公開されます。 {% data reusables.pages.pages-about-branch-source %}

{% endif %}
