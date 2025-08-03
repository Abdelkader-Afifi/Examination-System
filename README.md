# Examination-System
├── Examination-Api
    ├── Controllers
    │   ├── AuthController.cs
    │   ├── ExamsController.cs
    │   ├── QuestionsController.cs
    │   ├── ResultsController.cs
    │   ├── StudentExamsController.cs
    │   └── WeatherForecastController.cs
    ├── DataSeeding
    │   └── SeedData.cs
    ├── DbContexts
    │   └── DbContext.cs
    ├── DtoModel
    │   ├── AnswerSubmissionDto.cs
    │   ├── ExamDto.cs
    │   ├── ExamResponseDto.cs
    │   ├── LoginDto.cs
    │   ├── QuestionDto.cs
    │   ├── RegisterDto.cs
    │   └── RevokedToken.cs
    ├── Migrations
    │   ├── 20250707141359_FirstInit.Designer.cs
    │   ├── 20250707141359_FirstInit.cs
    │   ├── 20250709141816_AddRevokedToken.Designer.cs
    │   ├── 20250709141816_AddRevokedToken.cs
    │   ├── 20250713152849_Cascade.Designer.cs
    │   ├── 20250713152849_Cascade.cs
    │   ├── 20250713153442_Cascade2.Designer.cs
    │   ├── 20250713153442_Cascade2.cs
    │   └── AppDbContextModelSnapshot.cs
    ├── Models
    │   ├── Answer.cs
    │   ├── ApplicationUser.cs
    │   ├── Exam.cs
    │   ├── Option.cs
    │   ├── Question.cs
    │   └── Result.cs
    ├── Program.cs
    ├── Properties
    │   └── launchSettings.json
    ├── WeatherForecast.cs
    ├── WebApiAngular.csproj
    ├── WebApiAngular.csproj.user
    ├── WebApiAngular.http
    ├── appsettings.Development.json
    ├── appsettings.json
    ├── bin
    │   └── Debug
    │   │   └── net9.0
    │   │       ├── Azure.Core.dll
    │   │       ├── Azure.Identity.dll
    │   │       ├── Castle.Core.dll
    │   │       ├── Humanizer.dll
    │   │       ├── Microsoft.AspNetCore.Authentication.JwtBearer.dll
    │   │       ├── Microsoft.AspNetCore.Cryptography.Internal.dll
    │   │       ├── Microsoft.AspNetCore.Cryptography.KeyDerivation.dll
    │   │       ├── Microsoft.AspNetCore.Identity.EntityFrameworkCore.dll
    │   │       ├── Microsoft.AspNetCore.OpenApi.dll
    │   │       ├── Microsoft.Bcl.AsyncInterfaces.dll
    │   │       ├── Microsoft.Build.Locator.dll
    │   │       ├── Microsoft.CodeAnalysis.CSharp.Workspaces.dll
    │   │       ├── Microsoft.CodeAnalysis.CSharp.dll
    │   │       ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.dll
    │   │       ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.dll
    │   │       ├── Microsoft.CodeAnalysis.Workspaces.dll
    │   │       ├── Microsoft.CodeAnalysis.dll
    │   │       ├── Microsoft.Data.SqlClient.dll
    │   │       ├── Microsoft.EntityFrameworkCore.Abstractions.dll
    │   │       ├── Microsoft.EntityFrameworkCore.Design.dll
    │   │       ├── Microsoft.EntityFrameworkCore.Proxies.dll
    │   │       ├── Microsoft.EntityFrameworkCore.Relational.dll
    │   │       ├── Microsoft.EntityFrameworkCore.SqlServer.dll
    │   │       ├── Microsoft.EntityFrameworkCore.dll
    │   │       ├── Microsoft.Extensions.Caching.Abstractions.dll
    │   │       ├── Microsoft.Extensions.Caching.Memory.dll
    │   │       ├── Microsoft.Extensions.Configuration.Abstractions.dll
    │   │       ├── Microsoft.Extensions.Configuration.dll
    │   │       ├── Microsoft.Extensions.DependencyInjection.Abstractions.dll
    │   │       ├── Microsoft.Extensions.DependencyInjection.dll
    │   │       ├── Microsoft.Extensions.DependencyModel.dll
    │   │       ├── Microsoft.Extensions.Identity.Core.dll
    │   │       ├── Microsoft.Extensions.Identity.Stores.dll
    │   │       ├── Microsoft.Extensions.Logging.Abstractions.dll
    │   │       ├── Microsoft.Extensions.Logging.dll
    │   │       ├── Microsoft.Extensions.Options.dll
    │   │       ├── Microsoft.Extensions.Primitives.dll
    │   │       ├── Microsoft.Identity.Client.Extensions.Msal.dll
    │   │       ├── Microsoft.Identity.Client.dll
    │   │       ├── Microsoft.IdentityModel.Abstractions.dll
    │   │       ├── Microsoft.IdentityModel.JsonWebTokens.dll
    │   │       ├── Microsoft.IdentityModel.Logging.dll
    │   │       ├── Microsoft.IdentityModel.Protocols.OpenIdConnect.dll
    │   │       ├── Microsoft.IdentityModel.Protocols.dll
    │   │       ├── Microsoft.IdentityModel.Tokens.dll
    │   │       ├── Microsoft.OpenApi.dll
    │   │       ├── Microsoft.SqlServer.Server.dll
    │   │       ├── Microsoft.Win32.SystemEvents.dll
    │   │       ├── Mono.TextTemplating.dll
    │   │       ├── Swashbuckle.AspNetCore.SwaggerUI.dll
    │   │       ├── System.ClientModel.dll
    │   │       ├── System.CodeDom.dll
    │   │       ├── System.Composition.AttributedModel.dll
    │   │       ├── System.Composition.Convention.dll
    │   │       ├── System.Composition.Hosting.dll
    │   │       ├── System.Composition.Runtime.dll
    │   │       ├── System.Composition.TypedParts.dll
    │   │       ├── System.Configuration.ConfigurationManager.dll
    │   │       ├── System.Drawing.Common.dll
    │   │       ├── System.IdentityModel.Tokens.Jwt.dll
    │   │       ├── System.Memory.Data.dll
    │   │       ├── System.Runtime.Caching.dll
    │   │       ├── System.Security.Cryptography.ProtectedData.dll
    │   │       ├── System.Security.Permissions.dll
    │   │       ├── System.Windows.Extensions.dll
    │   │       ├── WebApiAngular.deps.json
    │   │       ├── WebApiAngular.dll
    │   │       ├── WebApiAngular.exe
    │   │       ├── WebApiAngular.pdb
    │   │       ├── WebApiAngular.runtimeconfig.json
    │   │       ├── WebApiAngular.staticwebassets.endpoints.json
    │   │       ├── appsettings.Development.json
    │   │       ├── appsettings.json
    │   │       ├── cs
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── de
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── es
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── fr
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── it
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── ja
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── ko
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── pl
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── pt-BR
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── ru
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── runtimes
    │   │           ├── unix
    │   │           │   └── lib
    │   │           │   │   └── net6.0
    │   │           │   │       ├── Microsoft.Data.SqlClient.dll
    │   │           │   │       └── System.Drawing.Common.dll
    │   │           ├── win-arm
    │   │           │   └── native
    │   │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │   │           ├── win-arm64
    │   │           │   └── native
    │   │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │   │           ├── win-x64
    │   │           │   └── native
    │   │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │   │           ├── win-x86
    │   │           │   └── native
    │   │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │   │           └── win
    │   │           │   └── lib
    │   │           │       └── net6.0
    │   │           │           ├── Microsoft.Data.SqlClient.dll
    │   │           │           ├── Microsoft.Win32.SystemEvents.dll
    │   │           │           ├── System.Drawing.Common.dll
    │   │           │           ├── System.Runtime.Caching.dll
    │   │           │           ├── System.Security.Cryptography.ProtectedData.dll
    │   │           │           └── System.Windows.Extensions.dll
    │   │       ├── tr
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       ├── zh-Hans
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │       └── zh-Hant
    │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │           └── Microsoft.CodeAnalysis.resources.dll
    └── obj
    │   ├── Debug
    │       └── net9.0
    │       │   ├── .NETCoreApp,Version=v9.0.AssemblyAttributes.cs
    │       │   ├── ApiEndpoints.json
    │       │   ├── WebApiAn.9E4B9F0F.Up2Date
    │       │   ├── WebApiAngular.AssemblyInfo.cs
    │       │   ├── WebApiAngular.AssemblyInfoInputs.cache
    │       │   ├── WebApiAngular.GeneratedMSBuildEditorConfig.editorconfig
    │       │   ├── WebApiAngular.GlobalUsings.g.cs
    │       │   ├── WebApiAngular.MvcApplicationPartsAssemblyInfo.cache
    │       │   ├── WebApiAngular.MvcApplicationPartsAssemblyInfo.cs
    │       │   ├── WebApiAngular.assets.cache
    │       │   ├── WebApiAngular.csproj.AssemblyReference.cache
    │       │   ├── WebApiAngular.csproj.BuildWithSkipAnalyzers
    │       │   ├── WebApiAngular.csproj.CoreCompileInputs.cache
    │       │   ├── WebApiAngular.csproj.FileListAbsolute.txt
    │       │   ├── WebApiAngular.dll
    │       │   ├── WebApiAngular.genruntimeconfig.cache
    │       │   ├── WebApiAngular.pdb
    │       │   ├── WebApiAngular.sourcelink.json
    │       │   ├── apphost.exe
    │       │   ├── ref
    │       │       └── WebApiAngular.dll
    │       │   ├── refint
    │       │       └── WebApiAngular.dll
    │       │   ├── rjsmcshtml.dswa.cache.json
    │       │   ├── rjsmrazor.dswa.cache.json
    │       │   ├── rpswa.dswa.cache.json
    │       │   ├── staticwebassets.build.endpoints.json
    │       │   ├── staticwebassets.build.json
    │       │   ├── staticwebassets.build.json.cache
    │       │   ├── staticwebassets.references.upToDateCheck.txt
    │       │   └── staticwebassets.removed.txt
    │   ├── WebApiAngular.csproj.nuget.dgspec.json
    │   ├── WebApiAngular.csproj.nuget.g.props
    │   ├── WebApiAngular.csproj.nuget.g.targets
    │   ├── project.assets.json
    │   └── project.nuget.cache
├── Examination-UI
    ├── .editorconfig
    ├── .gitignore
    ├── .vscode
    │   ├── extensions.json
    │   ├── launch.json
    │   └── tasks.json
    ├── README.md
    ├── angular.json
    ├── package-lock.json
    ├── package.json
    ├── public
    │   └── favicon.ico
    ├── src
    │   ├── app
    │   │   ├── admin
    │   │   │   ├── admin-module.ts
    │   │   │   ├── admin-routing-module.ts
    │   │   │   ├── admin.routes.ts
    │   │   │   ├── dashboard
    │   │   │   │   ├── dasboard-content
    │   │   │   │   │   ├── dasboard-content.css
    │   │   │   │   │   ├── dasboard-content.html
    │   │   │   │   │   ├── dasboard-content.spec.ts
    │   │   │   │   │   └── dasboard-content.ts
    │   │   │   │   ├── dashboard.css
    │   │   │   │   ├── dashboard.html
    │   │   │   │   ├── dashboard.spec.ts
    │   │   │   │   └── dashboard.ts
    │   │   │   ├── manage-exams
    │   │   │   │   ├── add-edit-exam
    │   │   │   │   │   ├── add-edit-exam.css
    │   │   │   │   │   ├── add-edit-exam.html
    │   │   │   │   │   ├── add-edit-exam.spec.ts
    │   │   │   │   │   └── add-edit-exam.ts
    │   │   │   │   ├── exam-list
    │   │   │   │   │   ├── exam-list.css
    │   │   │   │   │   ├── exam-list.html
    │   │   │   │   │   ├── exam-list.spec.ts
    │   │   │   │   │   └── exam-list.ts
    │   │   │   │   └── exams.routes.ts
    │   │   │   ├── manage-questions
    │   │   │   │   ├── add-edit-question
    │   │   │   │   │   ├── add-edit-question.css
    │   │   │   │   │   ├── add-edit-question.html
    │   │   │   │   │   ├── add-edit-question.spec.ts
    │   │   │   │   │   └── add-edit-question.ts
    │   │   │   │   ├── question-list
    │   │   │   │   │   ├── question-list.css
    │   │   │   │   │   ├── question-list.html
    │   │   │   │   │   ├── question-list.spec.ts
    │   │   │   │   │   └── question-list.ts
    │   │   │   │   └── questions.routes.ts
    │   │   │   └── results
    │   │   │   │   └── view-student-results
    │   │   │   │       ├── view-student-results.css
    │   │   │   │       ├── view-student-results.html
    │   │   │   │       ├── view-student-results.spec.ts
    │   │   │   │       └── view-student-results.ts
    │   │   ├── app.config.ts
    │   │   ├── app.css
    │   │   ├── app.html
    │   │   ├── app.routes.ts
    │   │   ├── app.spec.ts
    │   │   ├── app.ts
    │   │   ├── auth
    │   │   │   ├── auth.routes.ts
    │   │   │   ├── login
    │   │   │   │   ├── login.css
    │   │   │   │   ├── login.html
    │   │   │   │   ├── login.spec.ts
    │   │   │   │   └── login.ts
    │   │   │   └── register
    │   │   │   │   ├── register.css
    │   │   │   │   ├── register.html
    │   │   │   │   ├── register.spec.ts
    │   │   │   │   └── register.ts
    │   │   ├── core
    │   │   │   ├── ExamService
    │   │   │   │   └── exam-service.ts
    │   │   │   ├── admin-serveces
    │   │   │   │   ├── exam-service.spec.ts
    │   │   │   │   ├── exam-service.ts
    │   │   │   │   ├── question-service.spec.ts
    │   │   │   │   ├── question-service.ts
    │   │   │   │   ├── result-service.spec.ts
    │   │   │   │   └── result-service.ts
    │   │   │   ├── api.spec.ts
    │   │   │   ├── api.ts
    │   │   │   ├── auth-guard.spec.ts
    │   │   │   ├── auth-guard.ts
    │   │   │   ├── auth.spec.ts
    │   │   │   ├── auth.ts
    │   │   │   ├── result-service.ts
    │   │   │   ├── role-guard.spec.ts
    │   │   │   ├── role-guard.ts
    │   │   │   ├── test.spec.ts
    │   │   │   ├── test.ts
    │   │   │   └── token.interceptor.ts
    │   │   ├── shared
    │   │   │   ├── components
    │   │   │   │   └── navbar
    │   │   │   │   │   ├── navbar.css
    │   │   │   │   │   ├── navbar.html
    │   │   │   │   │   ├── navbar.spec.ts
    │   │   │   │   │   └── navbar.ts
    │   │   │   ├── models
    │   │   │   │   ├── ITest.ts
    │   │   │   │   ├── iexam-response.ts
    │   │   │   │   ├── iexam-result.ts
    │   │   │   │   ├── iexam.ts
    │   │   │   │   ├── iquestion.ts
    │   │   │   │   └── istudent-response.ts
    │   │   │   └── pipes
    │   │   │   │   ├── hooda.html
    │   │   │   │   ├── shorten-id-pipe.spec.ts
    │   │   │   │   └── shorten-id-pipe.ts
    │   │   └── student
    │   │   │   ├── dashboard
    │   │   │       ├── dashboard-content
    │   │   │       │   ├── dashboard-content.css
    │   │   │       │   ├── dashboard-content.html
    │   │   │       │   ├── dashboard-content.spec.ts
    │   │   │       │   └── dashboard-content.ts
    │   │   │       ├── dashboard.css
    │   │   │       ├── dashboard.html
    │   │   │       ├── dashboard.spec.ts
    │   │   │       └── dashboard.ts
    │   │   │   ├── exams
    │   │   │       ├── exam-list
    │   │   │       │   ├── exam-list.css
    │   │   │       │   ├── exam-list.html
    │   │   │       │   ├── exam-list.spec.ts
    │   │   │       │   └── exam-list.ts
    │   │   │       ├── submit-exam
    │   │   │       │   ├── submit-exam.css
    │   │   │       │   ├── submit-exam.html
    │   │   │       │   ├── submit-exam.spec.ts
    │   │   │       │   └── submit-exam.ts
    │   │   │       └── take-exam
    │   │   │       │   ├── take-exam.css
    │   │   │       │   ├── take-exam.html
    │   │   │       │   ├── take-exam.spec.ts
    │   │   │       │   └── take-exam.ts
    │   │   │   ├── results
    │   │   │       └── view-results
    │   │   │       │   ├── view-results.css
    │   │   │       │   ├── view-results.html
    │   │   │       │   ├── view-results.spec.ts
    │   │   │       │   └── view-results.ts
    │   │   │   ├── student-module.ts
    │   │   │   ├── student-routing-module.ts
    │   │   │   └── student.routes.ts
    │   ├── environments
    │   │   └── environments.ts
    │   ├── index.html
    │   ├── main.ts
    │   └── styles.css
    ├── tsconfig.app.json
    ├── tsconfig.json
    └── tsconfig.spec.json
