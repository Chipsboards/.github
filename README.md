#chipboards.github
Docs
#
@Composable public fun HelloCompose() { Column(modifier = Modifier.padding(16.dp)) { Text( text = "Hello!", modifier =ReadmeCompose Modifier.padding(bottom = 8.dp), style = MaterialTheme.typography.body.alignDefault ) OutlinedTextField( value = "0, 10, 20, 30, 40, 50, -50, -40, -30, -20, -10, 0", onValueChange = { }, label = { Text("chipboards") } ) } }

