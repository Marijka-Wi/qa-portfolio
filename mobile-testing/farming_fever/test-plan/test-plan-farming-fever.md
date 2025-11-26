**Introduction**

This Test Plan defines the testing approach, scope, objectives, environment, strategy, risks, and deliverables for testing the alpha version of the mobile game “Farming Fever.”

The purpose of this document is to ensure transparent, structured, and efficient testing aligned with the early stage of development.



**Product Overview**

Farming Fever is a mobile farming-management game where players grow crops, upgrade their farm, collect resources, fulfill orders, and progress through levels.

The current build is an early alpha (.apk) intended for internal evaluation of core gameplay, stability, UI/UX, and reward systems.



**Testing Objectives**

Validate core gameplay functionality

Identify high-impact defects affecting user flow

Evaluate UI/UX consistency

Verify the stability of the alpha build on a real device

Validate main systems: store, rewards, videos, upgrades

Provide recommendations to improve user experience



**Scope of Testing**

*IN SCOPE*

Installation \& first launch

Main menu \& navigation

Tutorial (if available)

Gameplay mechanics (harvesting, collecting, fulfilling orders)

Resource system (coins, gems, items)

Upgrades \& progression

Level transitions

Store \& in-game purchases

Daily rewards

Video ads (rewarded ads)

Sound \& music

UI/UX consistency

Performance basics (FPS drops, lags, freezes)

Stability \& crash detection





*OUT OF SCOPE*

Multiplayer or social features

Localization testing

Server-side validation

A/B testing

Monetization real-payment processing (sandbox only)

Long-term analytics or retention metrics

Load or stress testing



**Testing Approach / Strategy**



*Testing Types*



Type						Description



Functional testing			Validation of core mechanics and game flows

Exploratory testing			Adaptive exploration of gameplay edge cases

UI/UX testing				Layouts, readability, interactions, user flow

Compatibility testing			Testing on 1 Android device, OS version 14

Regression (partial)			Re-check critical paths after major bugs

Ad testing				Rewarded video behavior \& reward logic

Store testing				Purchase flow, reward assignment

Performance (basic)			Lags, animation issues, FPS drops





**Test Items**

APK installation package

Gameplay scenes (levels 1–12+)

In-game UI

Store \& rewarded ads

Upgrade system

Sound system

Daily rewards

Save/load system



**Features to Be Tested**

*Critical*

App launch

Level start \& completion

Resource updates (coins, gems, products)

Upgrades (farm, animals, tools)

Ads \& rewards

In-game currency store



*Medium*

Settings menu

Help \& info screens

Animations

Sound stability



*Low*

Visual polish

Minor UI misalignments



**Test Deliverables**

*The following artifacts will be produced:*



Test Plan (this document)

Test Cases

Checklist

Bug Report

Screenshots/Video Evidence

Final Test Report (PDF + MD)





**Test Environment**

*Hardware*

Xiaomi Redmi 14C

Screen: 6.67”, 120Hz

RAM: 8GB

CPU: Octa-core Max2.00 GHz

Storage: 256GB



*Software*

Android 14

Farming Fever APK (Alpha build)





**Tools**

Google Sheets / Excel

Screen recorder (native)

GitHub

Google Drive



**Risks \& Assumptions**



*Risks*

Alpha build may contain incomplete features

Debug GUI is available to players → may affect gameplay testing

Ads may not work in early build

Performance may vary significantly depending on device



*Assumptions*

No backend load testing required

Monetization systems use sandbox mode

Design is not final

Build may contain placeholder assets



**Entry / Exit Criteria**



*Entry Criteria*

APK build available

Device ready and charged

Basic documentation provided



*Exit Criteria*

All critical \& major bugs reported

Checklist executed

Core gameplay tested

Test report delivered

No blockers in tutorial, gameplay, or store



**Schedule**



Task					Date



Test execution			Nov 2–10, 2025

Bug reporting			Throughout testing

Final report preparation	Nov 10–12, 2025





**Approval**

QA Engineer: Maria Wittwer

Date: to be specified



