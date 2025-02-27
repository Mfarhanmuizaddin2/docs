---
title: Administrar tus recordatorios programados
intro: Obtén recordatorios en Slack cuando tú o tu equipo tenga solicitudes de extracción pendientes de revisión.
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Accounts
redirect_from:
  - /github/setting-up-and-managing-your-github-user-account/managing-your-scheduled-reminders
  - /github/setting-up-and-managing-your-github-user-account/managing-your-membership-in-organizations/managing-your-scheduled-reminders
shortTitle: Administrar los recordatorios programados
---

## Acerca de los recordatorios programados para usuarios

Los recordatorios programados se utilizan para garantizar que los usuarios se enfoquen en las solicitudes de revisión más importantes que requieren de su atención. Los recordatorios programados para solicitudes de extracción te enviarán un mensaje en Slack con las solicitudes de extracción que estén abiertas y necesiten de tu revisión en un periodo específico. Por ejemplo, puedes configurar tus recordatorios programados para que te envíen un mensaje en Slack cada mañana a las 10 AM con las solicitudes de extracción que requieren de tu revisión o de la de alguno de tus equipos.

Para ciertos eventos, también puedes habilitar las alertas en tiempo real para los recordatorios programados. Las alertas en tiempo real se envían a tu canal de Slack tan pronto se suscita un evento importante, tal como cuando se te asigna una revisión.

Puedes configurar recordatorios programados para solicitudes de revisión a nivel personal o a nivel de equipo para las solicitudes de extracción en las organizaciones de las cuales eres miembro. Antes de que puedas crear un recordatorio programado para ti mismo, un propietario de la organización debe autorizar tu espacio de trabajo en Slack. Para obtener más información, consulta la sección "[Administrar recordatorios programados para tu organización](/organizations/managing-organization-settings/managing-scheduled-reminders-for-your-organization)".

{% data reusables.reminders.scheduled-reminders-limitations %}

## Creating scheduled reminders for your personal account

{% data reusables.user-settings.access_settings %}
{% data reusables.reminders.scheduled-reminders %}
1. Da clic en **Editar** a un costado de la organización para la cual quieres programar un recordatorio. ![Botón de editar recordatorios programados](/assets/images/help/settings/scheduled-reminders-org-choice.png)
{% data reusables.reminders.add-reminder %}
{% data reusables.reminders.authorize-slack %}
{% data reusables.reminders.days-dropdown %}
{% data reusables.reminders.times-dropdowns %}
8. Opcionalmente, para recibir recordatorios programados para las revisiones a las cuales se te ha asignado, selecciona **Revisar las solicitudes que se te han asignado**. ![Casilla de revisar las solicitudes que se te han asignado](/assets/images/help/profile/scheduled-reminders-your-requests.png)
9. Opcionalmente, para recibir los recordatorios programados para las revisiones que se han asignado a algún equipo del cual seas miembro, selecciona **Revisar solicitudes asignadas a tu equipo**. ![Casilla de revisar las solicitudes que se han asignado a tu equipo](/assets/images/help/profile/scheduled-reminders-your-team-requests.png)
{% data reusables.reminders.real-time-alerts %}
![Casilla para habilitar las alertas en tiempo real](/assets/images/help/settings/scheduled-reminders-real-time-alerts-personal.png)
{% data reusables.reminders.create-reminder %}

## Managing scheduled reminders for your personal account
{% data reusables.user-settings.access_settings %}
{% data reusables.reminders.scheduled-reminders %}
1. Da clic en **Editar** a un costado de la organización para la cual quieres editar los recordatorios programados. ![Botón de editar recordatorios programados](/assets/images/help/settings/scheduled-reminders-org-choice.png)
{% data reusables.reminders.edit-page %}
{% data reusables.reminders.update-buttons %}

## Deleting scheduled reminders for your personal account
{% data reusables.user-settings.access_settings %}
{% data reusables.reminders.scheduled-reminders %}
1. Da clic en **Editar** a un costado de la organización para la cual quieres borrar un recordatorio. ![Botón de editar recordatorios programados](/assets/images/help/settings/scheduled-reminders-org-choice.png)
{% data reusables.reminders.delete %}

## Leer más

- "[Administrar los recordatorios programados para tu organización](/organizations/managing-organization-settings/managing-scheduled-reminders-for-your-organization)"
- "[Administrar los recordatorios programados para tu equipo](/organizations/organizing-members-into-teams/managing-scheduled-reminders-for-your-team)"
