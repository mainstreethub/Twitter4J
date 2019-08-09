import com.mainstreethub.jenkins.pipelines.Notifier
import com.mainstreethub.jenkins.pipelines.java.library.Pipeline

def notifier = new Notifier([
  steps: this,
  ownerChannels: ["gps-dify-content-noti"]
])

new Pipeline(this).run([
  notifier: notifier
])