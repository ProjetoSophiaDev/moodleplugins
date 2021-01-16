# moodleplugins
Moodle MOOC Plugins

## Upgrade Submodules
```bash
git submodule update --remote
```
## Disable Notifications

```php
 // Moodle configuration file
 
// Use the following flag to completely disable the installation of plugins
// (new plugins, available updates and missing dependencies) and related
// features (such as cancelling the plugin installation or upgrade) via the
// server administration web interface.
$CFG->disableupdateautodeploy = true;
// Disabling update notifications
$CFG->disableupdatenotifications = true;
```
## References
https://www.vogella.com/tutorials/GitSubmodules/article.html


## Plugins List

```bash
mkdir moodle
cd moodle
```

- https://github.com/markn86/moodle-mod_customcert
```bash
git submodule add -b MOODLE_38_STABLE https://github.com/markn86/moodle-mod_customcert.git mod/customcert
```
- https://github.com/danmarsden/moodle-mod_attendance/
```bash
git submodule add -b main https://github.com/danmarsden/moodle-mod_attendance.git mod/attendance
```
- https://github.com/blindsidenetworks/moodle-mod_bigbluebuttonbn
```bash
git submodule add -b v2.3-stable https://github.com/blindsidenetworks/moodle-mod_bigbluebuttonbn.git mod/bigbluebuttonbn
```
- https://github.com/FMCorz/moodle-block_xp
```bash
git submodule add -b master https://github.com/FMCorz/moodle-block_xp.git blocks/xp
```
- https://github.com/deraadt/moodle-block_completion_progress
```bash
git submodule add -b master https://github.com/deraadt/moodle-block_completion_progress.git blocks/completion_progress
```
- https://github.com/ndunand/moodle-mod_choicegroup
```bash
git submodule add -b master https://github.com/ndunand/moodle-mod_choicegroup.git mod/choicegroup
```
- https://github.com/dthies/moodle-atto_fullscreen
```bash
git submodule add -b master https://github.com/dthies/moodle-atto_fullscreen.git lib/editor/atto/plugins/fullscreen
```
- https://github.com/frankkoch/moodle-mod_studentquiz
```bash
git submodule add -b master https://github.com/frankkoch/moodle-mod_studentquiz.git mod/studentquiz
```
- https://github.com/mikasmart/moodle-report_benchmark
```bash
git submodule add -b master https://github.com/mikasmart/moodle-report_benchmark.git report/benchmark
```
- https://github.com/moodlehq/moodle-tool_migratehvp2h5p
```bash
git submodule add -b master https://github.com/moodlehq/moodle-tool_migratehvp2h5p.git admin/tool/migratehvp2h5p
```

- https://github.com/h5p/h5p-moodle-plugin
```bash
git submodule add -b stable https://github.com/h5p/h5p-moodle-plugin.git mod/hvp
cd mod/hvp
git submodule update --init
```
- https://github.com/dasistwas/moodle-mod_booking

```bash
git submodule add -b master https://github.com/dasistwas/moodle-mod_booking.git  mod/booking
```
- https://github.com/davosmith/moodle-checklist
```bash
git submodule add -b master https://github.com/davosmith/moodle-checklist.git mod/checklist
```
- https://github.com/bostelm/moodle-mod_scheduler
```bash
 git submodule add -b master https://github.com/bostelm/moodle-mod_scheduler.git mod/scheduler
```

- https://github.com/bdaloukas/moodle-mod_game
```bash
 git submodule add -b MOODLE_20_STABLE https://github.com/bdaloukas/moodle-mod_game.git mod/game
```

- https://github.com/moodleuulm/moodle-local_sandbox
```bash
git submodule add -b master https://github.com/moodleuulm/moodle-local_sandbox.git local/sandbox
```
- https://github.com/jleyva/moodle-block_configurablereports
```bash
git submodule add -b MOODLE_36_STABLE https://github.com/jleyva/moodle-block_configurablereports.git blocks/configurable_reports
```
- https://moodle.org/plugins/block_dedication
```bash
git submodule add -b MOODLE_30_STABLE https://bitbucket.org/ciceidev/moodle_block_dedication.git blocks/dedication
```

- https://github.com/mudrd8mz/moodle-mod_subcourse
```bash
git submodule add -b master https://github.com/mudrd8mz/moodle-mod_subcourse.git mod/subcourse
```

- https://github.com/academic-moodle-cooperation/moodle-mod_publication
```bash
git submodule add -b MOODLE_310_STABLE https://github.com/academic-moodle-cooperation/moodle-mod_publication.git mod/publication
```

- https://moodle.org/plugins/theme_moove
```bash
git submodule add -b master https://github.com/willianmano/moodle-theme_moove.git theme/moove
```

- https://moodle.org/plugins/availability_relativedate
```bash
git submodule add -b main https://github.com/ewallah/moodle-availability_relativedate.git availability/condition/relativedate
```

## Themes List

- https://github.com/lmsace/eguru

```bash
git submodule add -b master https://github.com/ProjetoSophiaDev/eguru.git theme/eguru
```

## How to remove a submodule
```bash
git submodule deinit <path_to_submodule>
git rm <path_to_submodule>
git commit -m "Removed submodule "
rm -rf .git/modules/<path_to_submodule>
```

## Removed

- https://github.com/lmsace/academi 
```bash
git submodule add -b master https://github.com/ProjetoSophiaDev/academi.git theme/academi
```
- https://github.com/lmsace/klass

```bash
git submodule add -b master https://github.com/ProjetoSophiaDev/klass.git theme/klass
```
- https://github.com/willianmano/moodle-theme_moove
```bash
git submodule add -b master https://github.com/willianmano/moodle-theme_moove.git theme/moove
```

- https://gitlab.com/jezhops/moodle-theme_adaptable
```bash
git submodule add -b master https://gitlab.com/jezhops/moodle-theme_adaptable.git theme/adaptable
```

- https://github.com/dbnschools/moodle-theme_fordson
```bash
git submodule add -b master https://github.com/dbnschools/moodle-theme_fordson.git theme/fordson
```

- https://github.com/michael-milette/moodle-local_mailtest
```bash
git submodule add -b master https://github.com/michael-milette/moodle-local_mailtest.git local/mailtest
```

- https://github.com/trema-tech/moodle-theme_trema

```bash
git submodule add -b MOODLE_38_STABLE https://github.com/trema-tech/moodle-theme_trema.git theme/trema
```



