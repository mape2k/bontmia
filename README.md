bontmia
=======

Bontmia - Backup Over Network To Multiple Incremental Archives

What is bontmia?
----------------

It stands for Backup Over Network To Multiple Incremental Archives and
is a network based backup with similar backup scheme as with tapes.
Saves configurable numbers of last month, week, day, hour and minute
backups. Each backup is a complete snapshot of the original
directories. Only new/changed files takes up space when generating a
new snapshot. Remote access is done over ssh.

Breaking Changes
----------------
* Version 0.20
  * rsync compression is disabled by default (instead of enabled by default)

COPYRIGHT
---------

Bontmia was written by John Enok Vollestad (john.enok@vollestad.no).
Bontmia may be used, modified and redistributed only under the terms
of the GNU General Public License, found in the file COPYING in this
distribution, or at http://www.fsf.org/licenses/gpl.html
