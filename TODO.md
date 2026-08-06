# Audio Player App - Implementation Steps

## Step 1: Update Configuration Files
- [x] Update `pubspec.yaml` with required dependencies
- [x] Update `AndroidManifest.xml` with audio permissions
- [x] Update `android/app/build.gradle.kts` with minSdk 21

## Step 2: Create Base Utilities & Models
- [x] Create `lib/models/audio_file.dart`
- [x] Create `lib/utils/constants.dart`
- [x] Create `lib/utils/format_utils.dart`

## Step 3: Create Services
- [x] Create `lib/services/audio_query_service.dart`
- [x] Create `lib/services/audio_player_service.dart`

## Step 4: Create Providers
- [x] Create `lib/providers/theme_provider.dart`
- [x] Create `lib/providers/audio_provider.dart`

## Step 5: Create Widgets
- [x] Create `lib/widgets/album_art_widget.dart`
- [x] Create `lib/widgets/song_list_tile.dart`
- [x] Create `lib/widgets/player_controls.dart`
- [x] Create `lib/widgets/player_slider.dart`
- [x] Create `lib/widgets/drawer_menu.dart`

## Step 6: Create Screens
- [x] Create `lib/screens/splash_screen.dart`
- [x] Create `lib/screens/home_screen.dart`
- [x] Create `lib/screens/player_screen.dart`

## Step 7: Update Main Entry Point
- [x] Update `lib/main.dart`

## Step 8: Install Dependencies & Verify
- [x] Run `flutter pub get`
- [x] All files verified

## Step 9: Add Sample Songs List
- [x] Create `lib/data/sample_songs.dart` with 20 popular songs (Indonesia & Internasional) with artist names
- [x] Update `lib/providers/audio_provider.dart` to use sample songs as fallback when no local songs found
