# Rules-for-CodeSniffer

<table>
    <thead>
        <th>Rule</th>
        <th>Namespase</th>
        <th>Description</th>
    </thead>
    <tbody>
<tr>
<td>Arrays.ArrayBracketSpacing</td>
<td>/Squiz.Arrays.ArrayBracketSpacing</td>
<td>Убедитесь, что вокруг квадратных скобок нет пробелов.</td>
</tr>
<tr>
<td>Arrays.ArrayDeclaration</td>
<td>/Squiz.Arrays.ArrayDeclaration</td>
<td>Обеспечивает соответствие массивов стандарту кодирования массивов.</td>
</tr>
<tr>
<td>Arrays.DisallowLongArraySyntax</td>
<td>/Generic.Arrays.DisallowLongArraySyntax</td>
<td>Запрещает использование синтаксиса длинных массивов PHP.</td>
</tr>
<tr>
<td>Arrays.DisallowShortArraySyntax</td>
<td>/Generic.Arrays.DisallowShortArraySyntax</td>
<td>Запрещает использование синтаксиса коротких массивов PHP.</td>
</tr>
<tr>
<td>Channels.IncludeSystem</td>
<td>/MySource.Channels.IncludeSystem</td>
<td>Обеспечивает включение систем, типов ресурсов и библиотек перед их использованием.</td>
</tr>
<tr>
<td>Classes.ClassDeclaration</td>
<td>/Squiz.Classes.ClassDeclaration</td>
<td>Проверяет правильность объявления класса и его наследования.</td>
</tr>
<tr>
<td>Classes.ClassFileName</td>
<td>/Squiz.Classes.ClassFileName</td>
<td>Проверяет соответствие имени файла и класса, содержащегося в файле.</td>
</tr>
<tr>
<td>Classes.DuplicateClassName</td>
<td>/Generic.Classes.DuplicateClassName</td>
<td>Сообщает об ошибках, если один и тот же класс или имя интерфейса используется в нескольких файлах.</td>
</tr>
<tr>
<td>CodeAnalysis.ForLoopShouldBeWhileLoop</td>
<td>/Generic.CodeAnalysis.ForLoopShouldBeWhileLoop</td>
<td>Обнаруживает циклы for, которые можно упростить до цикла while.</td>
</tr>
<tr>
<td>CodeAnalysis.ForLoopWithTestFunctionCall</td>
<td>/Generic.CodeAnalysis.ForLoopWithTestFunctionCall</td>
<td>Обнаруживает циклы for, которые используют вызов функции в тестовом выражении.</td>
</tr>
<tr>
<td>CodeAnalysis.UnconditionalIfStatement</td>
<td>/Generic.CodeAnalysis.UnconditionalIfStatement</td>
<td>Обнаруживает безусловные операторы if и elseif.</td>
</tr>
<tr>
<td>CodeAnalysis.UnusedFunctionParameter</td>
<td>/Generic.CodeAnalysis.UnusedFunctionParameter</td>
<td>Проверяет наличие неиспользуемых параметров функции.</td>
</tr>
<tr>
<td>CodeAnalysis.UselessOverridingMethod</td>
<td>/Generic.CodeAnalysis.UselessOverridingMethod</td>
<td>Обнаруживает ненужные переопределенные методы, которые просто вызывают своего родителя.</td>
</tr>
<tr>
<td>Commenting.EmptyCatchComment</td>
<td>/Squiz.Commenting.EmptyCatchComment</td>
<td>Проверяет наличие пустого предложения catch без комментария.</td>
</tr>
<tr>
<td>Commenting.InlineComment</td>
<td>/Squiz.Commenting.InlineComment</td>
<td>Проверяет наличие достаточного интервала между комментариями.</td>
</tr>
<tr>
<td>ControlStructures.ControlSignature</td>
<td>/Squiz.ControlStructures.ControlSignature</td>
<td>Проверяет, соответствуют ли операторы управления их стандартам кодирования.</td>
</tr>
<tr>
<td>ControlStructures.ForEachLoopDeclaration</td>
<td>/Squiz.ControlStructures.ForEachLoopDeclaration</td>
<td>Проверяет наличие пробела между каждым условием циклов foreach. </td>
</tr>
<tr>
<td>ControlStructures.ForLoopDeclaration</td>
<td>/Squiz.ControlStructures.ForLoopDeclaration</td>
<td>Проверяет наличие пробела между каждым условием цикла for </td>
</tr>
<tr>
<td>ControlStructures.InlineIfDeclaration</td>
<td>/Squiz.ControlStructures.InlineIfDeclaration</td>
<td>Проверяет интервалы сокращенных операторов IF. </td>
</tr>
<tr>
<td>ControlStructures.MultiLineCondition</td>
<td>/PEAR.ControlStructures.MultiLineCondition</td>
<td>Убедитесь, что условия многострочной IF определены правильно. </td>
</tr>
<tr>
<td>ControlStructures.SwitchDeclaration</td>
<td>/Squiz.ControlStructures.SwitchDeclaration</td>
<td>Обеспечивает форматирование оператора переключения. </td>
</tr>
<tr>
<td>Files.ClosingTag</td>
<td>/Zend.Files.ClosingTag</td>
<td>Проверяет, не заканчивается ли файл закрывающим тегом. </td>
</tr>
<tr>
<td>Files.EndFileNewline</td>
<td>/PSR2.Files.EndFileNewline</td>
<td>Гарантирует, что файл заканчивается символом новой строки. </td>
</tr>
<tr>
<td>Files.LineLength</td>
<td>/Generic.Files.LineLength</td>
<td>Проверяет длину всех строк в файле. </td>
</tr>
<tr>
<td>Formatting.DisallowMultipleStatements</td>
<td>/Generic.Formatting.DisallowMultipleStatements</td>
<td>Гарантирует, что каждый оператор находится в отдельной строке.</td>
</tr>
<tr>
<td>Formatting.MultiLineAssignment</td>
<td>/PEAR.Formatting.MultiLineAssignment</td>
<td>Если присвоение занимает более двух строк, убедитесь, что знак равенства находится с отступом.</td>
</tr>
<tr>
<td>Formatting.MultipleStatementAlignment</td>
<td>/Generic.Formatting.MultipleStatementAlignment</td>
<td>Проверяет соответствие назначений. </td>
</tr>
<tr>
<td>Functions.FunctionCallArgumentSpacing</td>
<td>/Generic.Functions.FunctionCallArgumentSpacing</td>
<td>Проверяет правильность размещения вызовов методов и функций.</td>
</tr>
<tr>
<td>Functions.FunctionCallSignature</td>
<td>/PEAR.Functions.FunctionCallSignature</td>
<td>Обеспечивает правильный формат вызовов функций.</td>
</tr>
<tr>
<td>Functions.FunctionDeclaration</td>
<td>/Squiz.Functions.FunctionDeclaration</td>
<td>Проверяет правильность объявления функции.</td>
</tr>
<tr>
<td>Functions.FunctionDeclarationArgumentSpacing</td>
<td>/Squiz.Functions.FunctionDeclarationArgumentSpacing</td>
<td>Проверяет правильность размещения аргументов в объявлениях функций.</td>
</tr>
<tr>
<td>Functions.FunctionDuplicateArgument</td>
<td>/Squiz.Functions.FunctionDuplicateArgument</td>
<td>Проверяет, не используются ли повторяющиеся аргументы в объявлениях функций.</td>
</tr>
<tr>
<td>Functions.GlobalFunction</td>
<td>/Squiz.Functions.GlobalFunction</td>
<td>Тесты на функции вне классов.</td>
</tr>
<tr>
<td>Functions.ValidDefaultValue</td>
<td>/PEAR.Functions.ValidDefaultValue</td>
<td>Гарантирует, что параметры функции со значениями по умолчанию находятся в конце объявления.</td>
</tr>
<tr>
<td>Methods.FunctionClosingBrace</td>
<td>/PSR2.Methods.FunctionClosingBrace</td>
<td>Проверяет, идет ли закрывающая скобка функции сразу после тела.</td>
</tr>
<tr>
<td>Metrics.NestingLevel</td>
<td>/Generic.Metrics.NestingLevel</td>
<td>Проверяет уровень вложенности методов.</td>
</tr>
<tr>
<td>Namespaces.NamespaceDeclaration</td>
<td>/PSR2.Namespaces.NamespaceDeclaration</td>
<td>Обеспечивает правильное объявление пространств имен.</td>
</tr>
<tr>
<td>Namespaces.UseDeclaration</td>
<td>/PSR2.Namespaces.UseDeclaration</td>
<td>Обеспечивает правильное объявление USE-блоков.</td>
</tr>
<tr>
<td>NamingConventions.ConstructorName</td>
<td>/Generic.NamingConventions.ConstructorName</td>
<td>Запрещает конструкторы стиля PHP 4.</td>
</tr>
<tr>
<td>NamingConventions.UpperCaseConstantName</td>
<td>/Generic.NamingConventions.UpperCaseConstantName</td>
<td>Гарантирует, что имена констант написаны заглавными буквами.</td>
</tr>
<tr>
<td>PHP.InnerFunctions</td>
<td>/Squiz.PHP.InnerFunctions</td>
<td>Гарантирует, что функции внутри функций никогда не используются.</td>
</tr>
<tr>
<td>PHP.LowerCaseConstant</td>
<td>/Generic.PHP.LowerCaseConstant</td>
<td>Проверяет, все ли значения true, false и null используются в нижнем регистре.</td>
</tr>
<tr>
<td>PHP.NonExecutableCode</td>
<td>/Squiz.PHP.NonExecutableCode</td>
<td>Предупреждает о коде, который никогда не может быть выполнен.</td>
</tr>
<tr>
<td>Scope.MemberVarScope</td>
<td>/Squiz.Scope.MemberVarScope</td>
<td>Проверяет наличие у членов класса модификаторов области видимости.</td>
</tr>
<tr>
<td>Scope.MethodScope</td>
<td>/Squiz.Scope.MethodScope</td>
<td>Проверяет, имеют ли методы класса модификаторы области видимости.</td>
</tr>
<tr>
<td>Scope.StaticThisUsage</td>
<td>/Squiz.Scope.StaticThisUsage</td>
<td>Проверяет использование $this в статических методах, что приведет к ошибкам выполнения.</td>
</tr>
<tr>
<td>WhiteSpace.DisallowSpaceIndent</td>
<td>/Generic.WhiteSpace.DisallowSpaceIndent</td>
<td>Выдает ошибки, если для отступа используются пробелы, отличные от точного.</td>
</tr>
<tr>
<td>WhiteSpace.FunctionClosingBraceSpace</td>
<td>/Squiz.WhiteSpace.FunctionClosingBraceSpace</td>
<td>Проверяет наличие одной пустой строки перед закрывающей фигурной скобкой функции.</td>
</tr>
<tr>
<td>WhiteSpace.FunctionOpeningBraceSpace</td>
<td>/Squiz.WhiteSpace.FunctionOpeningBraceSpace</td>
<td>Проверяет, нет ли пустой строки после открывающей фигурной скобки функции.</td>
</tr>
<tr>
<td>WhiteSpace.LogicalOperatorSpacing</td>
<td>/Squiz.WhiteSpace.LogicalOperatorSpacing</td>
<td>Проверяет наличие допустимого интервала между операторами.</td>
</tr>
<tr>
<td>PHP.DeprecatedFunctions</td>
<td>/Generic.PHP.DeprecatedFunctions</td>
<td>Не рекомендует использовать устаревшие функции PHP. </td>
</tr>
<tr>
<td>PHP.NoSilencedErrors</td>
<td>/Generic.PHP.NoSilencedErrors</td>
<td>Выдает ошибку или предупреждение, когда встречается любой код с префиксом asperand. </td>
</tr>
<tr>
<td>Functions.FunctionDeclarationArgumentSpacing</td>
<td>/Squiz.Functions.FunctionDeclarationArgumentSpacing</td>
<td>Проверяет правильность размещения аргументов в объявлениях функций. </td>
</tr>
    </tbody>
</table>