---
ms.openlocfilehash: eb37bb6abd26f8638202d7779b1919c4beda1d02
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: "146180588"
---
É importante escolher o motivo apropriado no menu suspenso, pois isso pode afetar se uma consulta continua sendo incluída em análise futura. {% ifversion comment-dismissed-code-scanning-alert %}Opcionalmente, você pode comentar sobre um alerta ignorado para registrar o contexto dele. O comentário sobre o alerta ignorado é adicionado à linha do tempo do alerta e pode ser usado como justificativa em auditorias e relatórios. Você pode recuperar ou definir um comentário usando a API REST de verificação de código. O comentário está contido no `dismissed_comment` do ponto de extremidade `alerts/{alert_number}`. Para obter mais informações, confira "[Verificação de código](/rest/code-scanning#update-a-code-scanning-alert)".
{% endif %}
