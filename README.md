# GitHub-auth0-auth0-java-README.md-path
GitHub-auth0/auth0-java-README.md-path - val roleId =  api.roles().list(RolesFilter()).execute().items.firstOrNull { it.name == roleName }?.id .... val users=api.roles().listUsers(roleId, PageFilter().withPage(offset / limit, limit).withTotals(true)).execute() 
