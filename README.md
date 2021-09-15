github_backup_software_archive
=============

Clone github's repositories found on https://github.com/github/dmca before takedown by DMCA. This fork will aim to modify the original project to submit repositories
to https://archive.softwareheritage.org/ .


//Currently at the planning stage
//
How to use ?
============

```
crontab -e
```

And put  
```
42 */6 * * * <path_to_github_backup>/github_backup.sh
```

Example :

```
42 */6 * * * /home/user/github_backup/github_backup.sh
```

Every 6 hours github_backup.sh will update dmca's local repository and backup new repositories found.
