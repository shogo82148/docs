---
title: プロジェクトボードの作成
intro: プロジェクトボードは、特定機能の働きの追跡と優先度付け、総合的なロードマップ、さらにはリリースチェックリストなど、ニーズを満たすカスタマイズワークフローを作成するために使用できます。
redirect_from:
  - /articles/creating-a-project/
  - /articles/creating-a-project-board
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

{{ site.data.reusables.project-management.use-automated-template }}

{{ site.data.reusables.project-management.copy-project-boards }}

{{ site.data.reusables.project-management.link-repos-to-project-board }}詳細は「[リポジトリをプロジェクトボードにリンクする](/articles/linking-a-repository-to-a-project-board)」を参照してください。

プロジェクトボードの作成が完了すると、そこへ Issue、プルリクエスト、およびノートを追加できます。 詳細は「[プロジェクトボードに Issue およびプルリクエストを追加する](/articles/adding-issues-and-pull-requests-to-a-project-board)」および「[プロジェクトボードにノートを追加する](/articles/adding-notes-to-a-project-board)」を参照してください。

また、プロジェクトボードが Issue やプルリクエストのステータスと同期を保てるよう、ワークフローの自動化を設定することもできます。 詳しい情報については「[プロジェクトボードの自動化について](/articles/about-automation-for-project-boards)」を参照してください。

{{ site.data.reusables.project-management.project-board-import-with-api }}

### ユーザが所有するプロジェクトボードの作成

{{ site.data.reusables.profile.access_profile }}
2. On the top of your profile page, in the main navigation, click
{% octicon "project" aria-label="The project board icon" %} **Projects**.
![プロジェクトタブ](/assets/images/help/projects/user-projects-tab.png)
{{ site.data.reusables.project-management.click-new-project }}
{{ site.data.reusables.project-management.create-project-name-description }}
{{ site.data.reusables.project-management.choose-template }}
{{ site.data.reusables.project-management.linked-repositories }}
{{ site.data.reusables.project-management.create-project-button }}
{{ site.data.reusables.project-management.add-column-new-project }}
{{ site.data.reusables.project-management.name-project-board-column }}
{{ site.data.reusables.project-management.select-column-preset }}
{{ site.data.reusables.project-management.select-automation-options-new-column }}
{{ site.data.reusables.project-management.click-create-column }}
{{ site.data.reusables.project-management.add-more-columns }}

{{ site.data.reusables.project-management.edit-project-columns }}

### Organization 全体のプロジェクトボードの作成

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.organization-wide-project }}
{{ site.data.reusables.project-management.click-new-project }}
{{ site.data.reusables.project-management.create-project-name-description }}
{{ site.data.reusables.project-management.choose-template }}
{{ site.data.reusables.project-management.linked-repositories }}
{{ site.data.reusables.project-management.create-project-button }}
{{ site.data.reusables.project-management.add-column-new-project }}
{{ site.data.reusables.project-management.name-project-board-column }}
{{ site.data.reusables.project-management.select-column-preset }}
{{ site.data.reusables.project-management.select-automation-options-new-column }}
{{ site.data.reusables.project-management.click-create-column }}
{{ site.data.reusables.project-management.add-more-columns }}

{{ site.data.reusables.project-management.edit-project-columns }}

### リポジトリのプロジェクトボードの作成

{{ site.data.reusables.repositories.navigate-to-repo }}
2. リポジトリ名の下で、クリックします
{% octicon "project" aria-label="The project board icon" %} **Projects**.
![プロジェクトタブ](/assets/images/help/projects/repo-tabs-projects.png)
{{ site.data.reusables.project-management.click-new-project }}
{{ site.data.reusables.project-management.create-project-name-description }}
{{ site.data.reusables.project-management.choose-template }}
{{ site.data.reusables.project-management.create-project-button }}
{{ site.data.reusables.project-management.add-column-new-project }}
{{ site.data.reusables.project-management.name-project-board-column }}
{{ site.data.reusables.project-management.select-column-preset }}
{{ site.data.reusables.project-management.select-automation-options-new-column }}
{{ site.data.reusables.project-management.click-create-column }}
{{ site.data.reusables.project-management.add-more-columns }}

{{ site.data.reusables.project-management.edit-project-columns }}

### 参考リンク

- "[プロジェクトボードについて](/articles/about-project-boards)"
- [プロジェクトボードの編集](/articles/editing-a-project-board){% if currentVersion == "free-pro-team@latest" %}
- [プロジェクトボードのコピー](/articles/copying-a-project-board)
{% endif %}
- "[プロジェクトボードをクローズする](/articles/closing-a-project-board)"
- [プロジェクトボードの自動化について](/articles/about-automation-for-project-boards)