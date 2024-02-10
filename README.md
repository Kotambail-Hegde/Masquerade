# Masquerade

For the latest release, CONFIG.ini as shown below is required for the application to start



[gameengine]
_version=f84f30da
_engine=OLC
_key=XXXXXXXXXX

[updater]
_repository=git@github.com:Kotambail-Hegde/Masquerade.git
_key=XXXXXXXXXX

[ui]
_sprite_menu_directory=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\ui\sprites\RetroMenu4.png
_sprite_bg_directory=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\ui\sprites\BG5.png
_rom_directory=C:\Data\Workspace\Emulators\Roms
_working_directory=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\internal
_key=XXXXXXXXXX

[gameoflife]
_id=8
_enableCustomDimensions=false
_screenHeight=256
_screenWidth=1024
_pixelHeight=1
_pixelWidth=1
_isTorroidal=true
_save_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\saves
_key=XXXXXXXXXX

[chip8]
_id=1
_chip8=true
_schip=false
_xo_chip=false
_bpv1_in_hex=true
_v0=-1
_v1=-1
_v2=-1
_v3=-1
_v4=-1
_v5=-1
_v6=-1
_v7=-1
_v8=-1
_v9=-1
_v10=-1
_v11=-1
_v12=-1
_v13=-1
_v14=-1
_v15=-1
_I=-1
_PC=-1
_SP=-1
_DT=-1
_ST=-1
_QUIRK_VF_RESET=false
_QUIRK_MEMORY=false
_QUIRK_DISPLAY_WAIT=false
_QUIRK_CLIP=false 
_QUIRK_SHIFT=false 
_QUIRK_JUMP=false
_save_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\saves
_key=XXXXXXXXXX

[spaceinvaders]
_id=6
_test_to_run=-1
_bpv1_in_hex=true
_A=-1
_F=-1
_B=-1
_C=-1
_D=-1
_E=-1
_H=-1
_L=-1
_PC=-1
_SP=-1
_DIP3=true
_DIP5=true
_DIP6=true
_DIP7=true
_audio_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\spaceInvaders\audio
_save_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\saves
_key=XXXXXXXXXX

[pacman]
_id=7
_test_to_run=-1
_bpv1_in_hex=true
_A=-1
_F=-1
_B=-1
_C=-1
_D=-1
_E=-1
_H=-1
_L=-1
_I=-1
_R=-1
_IXH=-1
_IXL=-1
_IYH=-1
_IYL=-1
_PC=-1
_SP=-1
_SHADOW_A=-1
_SHADOW_F=-1
_SHADOW_B=-1
_SHADOW_C=-1
_SHADOW_D=-1
_SHADOW_E=-1
_SHADOW_H=-1
_SHADOW_L=-1
_save_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\saves
_key=XXXXXXXXXX

[nes]
_id=2
_key=XXXXXXXXXX

[gb-gbc]
_id=3
_use_dmg_bios=false
_dmg_bios_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\gb\bios
_use_cgb_bios=false
_cgb_bios_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\gbc\bios
_force_shader=NO_SHADER
_force_gb_palette=PALETTE_1
_force_gb_gfx_for_gbc=false
_force_gb_for_gbc=false
_force_gbc_for_gb=false
_enable_cgb_color_correction=true
# Always keep the below Audio HPF enabled as this is used to remove the dc bias of the DACs!
_enable_audio_hpf=true
_enable_pixel_pipeline=true
_unacc_delay_cycles_gb=6
# Keeping "_unacc_delay_cycles_gbc" 2 gets "prehistorik man" in DMG compatibility mode properly aligned (Intro Screen)
# Keeping "_unacc_delay_cycles_gbc" 0 - 3 gets "denshe de go! 2" and "aladdin" working
# Keeping "_unacc_delay_cycles_gbc" 4 - 7 gets MTS ppu tests for gbc working
# Keeping "_unacc_delay_cycles_gbc" 19 - 22 gets "mezase" (pokemon jap intro) working
_unacc_delay_cycles_gbc=2
_save_location=C:\Data\Workspace\Emulators\Masquerade-(Multi-Console)\Prototype-10\masquerade\assets\saves
_key=XXXXXXXXXX

[snes]
_id=2
_key=XXXXXXXXXX

[n64]
_id=3
_key=XXXXXXXXXX

[gba]
_id=4
_key=XXXXXXXXXX

[gamecube]
_id=5
_key=XXXXXXXXXX

[ds]
_id=6
_key=XXXXXXXXXX

[wii]
_id=7
_key=XXXXXXXXXX

[3ds]
_id=8
_key=XXXXXXXXXX

[wiiu]
_id=9
_key=XXXXXXXXXX

[switch]
_id=10
_key=XXXXXXXXXX

[masquerade]
_version=0.5
_id=0
_key=XXXXXXXXXX

[mods]
_ENABLE_AUDIO=true
_IF_AUDIO_ENABLED_MUTE_IT=false
_ENABLE_DEBUG_LOG=false
_ENABLE_FRAME_LIMIT=false
_ENABLE_QUICK_SAVE=true
_ENABLE_REWIND=false
_REWIND_BUFFER_SIZE=5000
_key=XXXXXXXXXX

[debug]
_DEBUG_CALLSTACK=false
_DEBUG_DEBUGGER=false
_DEBUG_DEBUGGER_TRIGGER=71
_DEBUG_FPS=false
_DEBUG_MEMORY=false
_DEBUG_PROFILER=false
_DEBUG_REGISTERS=false
_key=XXXXXXXXXX