## Laravel Zero Foundation

This is a mirror of `src/Illuminate/Foundation` from [Laravel Framework](https://github.com/laravel/framework).

## Notes

In this package, `Illuminate\Foundation\Application` class doesn't implement `Symfony\Component\HttpKernel\HttpKernelInterface` interface.
The constant `MAIN_REQUEST` is copied in from `HttpKernelInterface`.

Also in this package, the `Console\Kernel::load()` method does not use the canonicalized absolute path to the `app` directory.

The `Illuminate\Foundation\Testing\Concerns\InteractsWithTestCaseLifecycle` class also has been modified to only run the queue teardown when the `Queue` class exists.

See [`bin/sync`](bin/sync) for a full list of automated changes.

## Support the development
**Do you like this project? Support it by donating**

- PayPal: [Donate](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=66BYDWAT92N6L)
- Patreon: [Donate](https://www.patreon.com/nunomaduro)

## License

Laravel Zero Foundation is open-sourced software licensed under the [MIT license](LICENSE.md).
