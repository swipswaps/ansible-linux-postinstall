.. code-block:: bash
   :emphasize-lines: 1

   shell> ansible-playbook linux-postinstall.yml --list-tags
   
   playbook: linux-postinstall.yml

   play #1 (srv.example.com): srv.example.com TAGS: []
      TASK TAGS: [always, lp_acpi, lp_acpi_actions, lp_acpi_events,
      lp_aliases, lp_apparmor, lp_apparmor_disable,
      lp_apparmor_enforce, lp_apparmor_packages, lp_apparmor_profiles,
      lp_apparmor_service, lp_authorized_keys, lp_auto_upgrades,
      lp_autofs, lp_bluetooth, lp_bluetooth_conf, lp_bluetooth_debug,
      lp_bluetooth_disable, lp_bluetooth_enable, lp_cron, lp_cron_tab,
      lp_cron_var, lp_debsums, lp_debsums_debug,
      lp_debsums_default_conf, lp_debsums_ignore_conf,
      lp_debsums_packages, lp_debug, lp_fstab, lp_gpg,
      lp_gpg_agent_conf, lp_gpg_conf, lp_gpg_debug,
      lp_gpg_dirmngr_conf, lp_gpg_packages, lp_gpsd, lp_gpsd_bt_rfcom,
      lp_gpsd_config, lp_gpsd_group, lp_gpsd_packages,
      lp_gpsd_service, lp_grub, lp_grub_conf, lp_grub_debug,
      lp_hostname, lp_hosts, lp_hosts_conf, lp_hosts_debug,
      lp_iptables, lp_kvm, lp_kvm_debug, lp_kvm_packages, lp_latex,
      lp_latex_dir, lp_latex_labels, lp_latex_macros,
      lp_latex_packages, lp_libvirt, lp_libvirt_conf,
      lp_libvirt_debug, lp_libvirt_guests_service,
      lp_libvirt_libvirtd_service, lp_libvirt_pkg, lp_lid,
      lp_logrotate, lp_modemmanager, lp_modules, lp_netplan, lp_nfsd,
      lp_nfsd_exports, lp_nfsd_packages, lp_nfsd_service, lp_packages,
      lp_packages_auto, lp_packages_debug, lp_packages_install,
      lp_packages_remove, lp_packages_selections_postinstall,
      lp_packages_selections_preinstall, lp_passwords,
      lp_passwords_debug, lp_passwords_passwordstore, lp_pm,
      lp_postfix, lp_postfix_conf, lp_postfix_debug,
      lp_postfix_service, lp_reboot, lp_repos, lp_repos_debug,
      lp_repos_keys_manage, lp_repos_manage, lp_resolvconf,
      lp_resolvconf_confd_head, lp_resolvconf_debug,
      lp_resolvconf_packages, lp_resolvconf_service, lp_service,
      lp_service_auto, lp_service_debug, lp_service_general, lp_smart,
      lp_smart_conf, lp_smart_packages, lp_smart_service, lp_speechd,
      lp_ssh, lp_ssh_conf, lp_ssh_debug, lp_sshd, lp_sshd_config,
      lp_sshd_debug, lp_sshd_service, lp_sudoers, lp_sudoers_conf,
      lp_sudoers_dconf, lp_sudoers_debug, lp_swap, lp_swap_debug,
      lp_swap_fstab, lp_swap_swapfile, lp_sysctl, lp_sysctl_debug,
      lp_timesyncd, lp_timesyncd_conf, lp_timesyncd_debug,
      lp_timesyncd_service, lp_timezone, lp_timezone_debug,
      lp_timezone_set, lp_tlp, lp_tlp_conf, lp_tlp_debug,
      lp_tlp_packages, lp_tlp_service, lp_udev, lp_udev_debug,
      lp_udev_hciname, lp_udev_hcirun, lp_udev_persistentnet,
      lp_udev_rules, lp_udev_service, lp_ufw, lp_ufw_conf,
      lp_ufw_debug, lp_ufw_packages, lp_ufw_reload, lp_ufw_reset,
      lp_ufw_service, lp_users, lp_users_accounts, lp_users_debug,
      lp_users_groups, lp_vars, lp_virtualbox, lp_virtualbox_debug,
      lp_virtualbox_keys, lp_virtualbox_pkg, lp_virtualbox_repos,
      lp_virtualbox_services, lp_wpa_action_script_dir,
      lp_wpa_action_script_file, lp_wpagui, lp_wpagui_debug,
      lp_wpagui_disableNM, lp_wpagui_mask_NM, lp_wpagui_packages,
      lp_wpasupplicant, lp_wpasupplicant_conf, lp_wpasupplicant_debug,
      lp_wpasupplicant_packages, lp_xen, lp_xen_debug,
      lp_xen_default_grub, lp_xen_global, lp_xen_packages, lp_xorg,
      lp_xorg_conf, lp_xorg_debug, lp_zeitgeist, lp_zfs, lp_zfs_debug,
      lp_zfs_manage, lp_zfs_mountpoints, lp_zfs_packages,
      lp_zfs_services]
