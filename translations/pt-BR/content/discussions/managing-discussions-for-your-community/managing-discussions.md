---
title: Gerenciando discussões
intro: 'Você pode categorizar, destacar e transferir ou excluir as discussões.'
permissions: Repository administrators and people with write or greater access to a repository can manage discussions in the repository. Repository administrators and people with write or greater access to the source repository for organization discussions can manage discussions in the organization.
versions:
  feature: discussions
shortTitle: Manage discussions
redirect_from:
  - /discussions/managing-discussions-for-your-community/managing-discussions-in-your-repository
ms.openlocfilehash: 95e806959eef023fd05e91a43f9269c98b5db052
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: '147786211'
---
## Sobre o gerenciamento de discussões

{% data reusables.discussions.about-discussions %} Para obter mais informações sobre as discussões, confira "[Sobre as discussões](/discussions/collaborating-with-your-community-using-discussions/about-discussions)".

Os proprietários da organização podem escolher as permissões necessárias para criar uma discussão em repositórios pertencentes à organização. Da mesma forma, para escolher as permissões necessárias para criar uma discussão da organização, os proprietários da organização podem alterar as permissões necessárias no repositório de origem. Para obter mais informações, confira "[Como gerenciar a criação de discussões para repositórios na sua organização](/organizations/managing-organization-settings/managing-discussion-creation-for-repositories-in-your-organization)".

Como mantenedor de discussões, você pode criar recursos da comunidade para incentivar discussões alinhadas com o objetivo geral do projeto e manter um fórum aberto amigável para os colaboradores. Criar{% ifversion fpt or ghec %} um código de conduta ou{% endif %} diretrizes de contribuição para os colaboradores a seguir ajudará a facilitar um fórum colaborativo e produtivo. Para obter mais informações sobre como criar recursos da comunidade, confira{% ifversion fpt or ghec %} "[Como adicionar um código de conduta ao seu projeto](/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project)" e{% endif %} "[Como definir diretrizes para colaboradores do repositório](/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)".

Quando uma discussão fornece uma ideia ou um erro que está pronto para ser trabalhado, você pode criar um novo problema a partir de uma discussão. Para obter mais informações, confira "[Como criar um problema](/issues/tracking-your-work-with-issues/creating-an-issue#creating-an-issue-from-a-discussion)".

Para obter mais informações sobre como facilitar uma discussão útil, confira "[Como moderar comentários e conversas](/communities/moderating-comments-and-conversations)".

{% data reusables.discussions.you-can-label-discussions %}

## Pré-requisitos

Para gerenciar as discussões em um repositório, {% data variables.product.prodname_discussions %} deve estar habilitado para o repositório. Para obter mais informações, confira "[Como habilitar ou desabilitar o {% data variables.product.prodname_discussions %} para um repositório](/github/administering-a-repository/enabling-or-disabling-github-discussions-for-a-repository)".

Para gerenciar as discussões em uma organização, o {% data variables.product.prodname_discussions %} deve estar habilitado na organização. Para obter mais informações, confira "[Como habilitar ou desabilitar o {% data variables.product.prodname_discussions %} em uma organização](/organizations/managing-organization-settings/enabling-or-disabling-github-discussions-for-an-organization)".

## Alterar a categoria para uma discussão

Você pode categorizar discussões para ajudar os integrantes da comunidade a encontrar discussões relacionadas. Para obter mais informações, confira "[Gerenciar categorias para discussões](/discussions/managing-discussions-for-your-community/managing-categories-for-discussions)".

Você também pode mover a discussão para uma categoria diferente. Não é possível mover uma discussão para ou da categoria de votação.

{% data reusables.repositories.navigate-to-repo %} {% data reusables.discussions.discussions-tab %} {% data reusables.discussions.click-discussion-in-list %}
1. Na barra lateral direita, à direita da "Categoria", clique em {% octicon "gear" aria-label="The gear icon" %}.
  !["Categoria" com o ícone de engrenagem](/assets/images/help/discussions/category-in-sidebar.png)
1. Clique em uma categoria.
  ![Menu suspenso "Alterar categoria"](/assets/images/help/discussions/change-category-drop-down.png)

## Fixar uma discussão

Você pode fixar até quatro discussões importantes acima da lista de discussões do repositório ou da organização.

{% data reusables.discussions.navigate-to-repo-or-org %} {% data reusables.discussions.discussions-tab %} {% data reusables.discussions.click-discussion-in-list %}
1. Na barra lateral direita, clique em {% octicon "pin" aria-label="The pin icon" %} **Fixar discussão**.
  !["Fixar discussão" na barra lateral direita da discussão](/assets/images/help/discussions/click-pin-discussion.png)
1. Opcionalmente, personalize a aparência da discussão fixada.
  ![Opções de personalização para uma discussão fixa](/assets/images/help/discussions/customize-pinned-discussion.png)
1. Clique em **Fixar discussão**.
  ![Botão "Fixar discussão" nas opções de personalização da discussão fixa](/assets/images/help/discussions/click-pin-discussion-button.png)

## Editar uma discussão fixada

Editar uma discussão fixada não irá alterar a categoria da discussão. Para obter mais informações, confira "[Gerenciar categorias para discussões](/discussions/managing-discussions-for-your-community/managing-categories-for-discussions)".

{% data reusables.discussions.navigate-to-repo-or-org %} {% data reusables.discussions.discussions-tab %} {% data reusables.discussions.click-discussion-in-list %}
1. Na barra lateral direita, clique em {% octicon "pencil" aria-label="The pencil icon" %} **Editar discussão fixa**.
  !["Editar discussão fixa" na barra lateral direita da discussão](/assets/images/help/discussions/click-edit-pinned-discussion.png)
1. Personalize a aparência da discussão fixada.
  ![Opções de personalização para uma discussão fixa](/assets/images/help/discussions/customize-pinned-discussion.png)
1. Clique em **Fixar discussão**.
  ![Botão "Fixar discussão" nas opções de personalização da discussão fixa](/assets/images/help/discussions/click-pin-discussion-button.png)

## Desafixar uma discussão

{% data reusables.discussions.navigate-to-repo-or-org %} {% data reusables.discussions.discussions-tab %} {% data reusables.discussions.click-discussion-in-list %}
1. Na barra lateral direita, clique em {% octicon "pin" aria-label="The pin icon" %} **Desafixar discussão**.
  !["Desafixar discussão" na barra lateral direita da discussão](/assets/images/help/discussions/click-unpin-discussion.png)
1. Leia o aviso e clique em **Desafixar discussão**.
  ![Botão "Desafixar discussão" abaixo do aviso na caixa de diálogo modal](/assets/images/help/discussions/click-unpin-discussion-button.png)

## Transferir uma discussão

Para transferir uma discussão, você precisa ter permissão de criar discussões no repositório, em que você deseja transferir a discussão. Se você quiser transferir uma discussão para uma organização, deverá ter permissões para criar discussões no repositório de origem das discussões da organização. Você somente pode transferir discussões entre repositórios pertencentes à mesma conta de usuário ou organização. Você não pode transferir uma discussão de um repositório privado{% ifversion ghec or ghes %} ou interno{% endif %} para um repositório público.

{% data reusables.discussions.navigate-to-repo-or-org %} {% data reusables.discussions.discussions-tab %} {% data reusables.discussions.click-discussion-in-list %}
1. Na barra lateral direita, clique em {% octicon "arrow-right" aria-label="The right arrow icon" %} **Transferir discussão**.
  !["Transferir discussão" na barra lateral direita da discussão](/assets/images/help/discussions/click-transfer-discussion.png)
1. Selecione o menu suspenso **Escolher um repositório** e clique no repositório para o qual deseja transferir a discussão. Se você quiser transferir uma discussão para uma organização, escolha o repositório de origem das discussões da organização.
  ![Menu suspenso "Escolher um repositório", campo de pesquisa "Localizar um repositório" e repositório na lista](/assets/images/help/discussions/use-choose-a-repository-drop-down.png)
1. Clique em **Transferir discussão**.
  ![Botão "Transferir discussão"](/assets/images/help/discussions/click-transfer-discussion-button.png)

## Excluir uma discussão

{% data reusables.discussions.navigate-to-repo-or-org %} {% data reusables.discussions.discussions-tab %} {% data reusables.discussions.click-discussion-in-list %}
1. Na barra lateral direita, clique em {% octicon "trash" aria-label="The trash arrow icon" %} **Excluir discussão**.
  !["Excluir discussão" na barra lateral direita da discussão](/assets/images/help/discussions/click-delete-discussion.png)
1. Leia o aviso e clique em **Excluir esta discussão**.
  ![Botão "Excluir esta discussão" abaixo do aviso na caixa de diálogo modal](/assets/images/help/discussions/click-delete-this-discussion-button.png)

## Converter problemas com base em etiquetas

Você pode converter todos as etiquetas com a mesma etiqueta para discussões em massa. Os problemas futuros com essa etiqueta também serão automaticamente convertidos em discussão e categoria que você configurar.

1. No {% data variables.product.product_location %}, navegue até a página principal do repositório ou, para discussões da organização, o repositório de origem.
{% data reusables.repositories.sidebar-issues %} {% data reusables.project-management.labels %}
1. Ao lado do rótulo que deseja converter em problemas, clique em **Converter problemas**.
1. Selecione o menu suspenso **Escolher uma categoria** e clique em uma categoria para ver a discussão.
1. Clique em **Entendi. Converter este problema em uma discussão**.
