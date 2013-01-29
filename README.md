qmail-custom-error-patch
========================

Qmail custom error patch non-official for FreeBSD qmail-spamcontrol's port version 2624

--

Patch (qmail-queue-custom-error.patch) made by Flavio Curti <fcu-software at no-way.org>.
Allows qmail-queue to exit using custom error-messages, which can be displayed on SMTP connections.
See file README.qq-custom-error after patching for details.
https://no-way.org/qmail-error/

--

For use only with qmail-spamcontrol's port version 2624 (FreeBSD).

Official patch fails when try to apply #1 Hunk on qmail.c after has been patched by qmail-spamcontrol port.
