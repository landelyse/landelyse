<a href="https://github.com/devxb/gitanimals">
<img
  src="https://render.gitanimals.org/lines/jbnong07"
  width="300"
  height="300"
  contribution-view=false
/>
</a>

<a href="https://github.com/devxb/gitanimals">
  <img
    src="https://render.gitanimals.org/lines/jbnong07?pet-id=647041219383512079"
    width="300"
    height="300"
  />
</a>

@MainActor
    func getImage(from imagePath: String?) async {
        do {
            self.image = try await detailViewOperator.fetchImage(from: imagePath)
        } catch {
            self.isErrorPresented = true
            self.errorMessage = error.localizedDescription
            print("[\((#file as NSString).lastPathComponent)] [\(#function): \(#line)] - error 났음")
        }
    }
  

<a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=jbnong07&utm_content=line">
  <img
    src="https://render.gitanimals.org/lines/jbnong07?pet-id=655289669593457305"
    width="600"
    height="120"
  />
</a>
  
