Connect to a running instance of the current app.

## Usage
~~~
flyctl ssh console [flags]
~~~

## Options

~~~
  -A, --address string   Address of VM to connect to
  -a, --app string       Application name
  -C, --command string   command to run on SSH session
  -c, --config string    Path to application configuration file
  -h, --help             help for console
  -o, --org string       The target Fly organization
      --pty              Allocate a pseudo-terminal (default: on when no command is provided)
  -q, --quiet            Don't print progress indicators for WireGuard
  -r, --region string    The target region (see 'flyctl platform regions')
  -s, --select           select available instances
  -u, --user string      Unix username to connect as (default "root")
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
      --debug                 Print additional logs and traces
      --verbose               Verbose output
~~~

## See Also

* [flyctl ssh](/docs/flyctl/ssh/)	 - Use SSH to login to or run commands on VMs

