# cmc2392tiger.github.io

     var OneSignal = window.OneSignal || [];
        OneSignal.push(function () {
            OneSignal.init({
                appId: "ec12774c-5271-45ff-8741-447e607f22bb",
                promptOptions: {
                    actionMessage: "Please allow Push Notification so we can Update you after Streaming issue is fixed.",
                    acceptButtonText: "ALLOW",
                    cancelButtonText: "NO THANKS"
                },
                notifyButton: {
                    enable: false
                },
                autoResubscribe: true,
                showCredit: false
            });
            OneSignal.push(function () {
                OneSignal.showHttpPrompt();
            });
        });
